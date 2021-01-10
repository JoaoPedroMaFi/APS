# Sprint planning & documentation #

In order to prepare the 1st sprint, the UC are split into Use Case Slices (UCS).

## Narratives of high priority UC ##
Considering the above table, 2 UC are in high priority.

Use case: Purchase ticket (UC1.01)
Basic Flow	Alternative Flows
1 Select purchase ticket	A1. Select another day
2 Show menu	A2. Select different canteen
3 Select dish	A3. No menu in selected date
4 Create a new ticket	A4. Insufficient account balance
5 Update user account	...
Use case: Validate ticket (UC2.01)
Basic Flow	Alternative Flows
1 Insert username	A1. Username not found
2 Show ticket	A2. No ticket available
3 Confirm ticket use	A3. Connection unavailable
...	A4. Negative account balance
User stories for UC1.01 and UC 2.01
In order to prepare the next sprint, the UC are split into user stories. For each use case, the set of user stories must complete the use case full behaviour.

Each user story form a work item that is of clear value to the customer.

US1.1a As a user, I want to buy a meal ticket so that I can take my lunch/dinner meal on IPCA Campus.

US1.1b As a user, I want to buy the meal tickets for lunch/dinner to the week and for any IPCA's canteen, so that I just need to worry once a week and do not forget to buy any ticket.

US1.1c As a user, I want to buy a meal ticket even when my account balance is not enough, so that I avoid to pay the extra price of the ticket purchased at the POS.

US2.1a As a cashier, I want to validate the user ticket so that I can confirm the user can receive a meal.

US2.1b As a cashier, I want check the user tickets so that I can consult the user login, the account balance and the last tickets bought by the user.

US2.1c As a cashier, I want to validate the ticket of a user with negative account balance, so that the user can load money to his/her account to get access to the meal.

Sprint planning
Both use cases are detailed into user stories in next table. BF stands for Basic Flow and A# stands for the alternatives flows. The 3rd Sprint Backlog (SB) will include the UCS marked with a "X".

UC	User story	Flows	estimate	3rd SB
1.1 Purchase ticket	1.1a Default date meal	BF	3d	X
1.1 Purchase ticket	1.1b Select canteen and day	BF, A1, A2	2d	X
1.1 Purchase ticket	1.1c Not enough credit	BF, A3, A4	4h	
2.1 Validate ticket	2.1a Valid ticket	BF	2d	X
2.1 Validate ticket	2.1b No ticket available	BF, A1, A2, A3	1d	
2.1 Validate ticket	2.1c Insufficient account balance	BF, A4	2d	
Important note Update JIRA, adding to the use cases (Epics) that were analyzed the respective user stories, ordered by their priority.

The acceptance tests
Example of Acceptance tests for the user stories included in third sprint.

Acceptance tests for US1.1a Default date meal (Purchase ticket)
Try to create a ticket without existing menu
Try different dish options
Check the ticket was correctly created for the user
Check the user credit was correctly updated
Verify the ticket refers the current date and selected dish
Acceptance tests for US1.1b Select canteen and day (Purchase ticket)
Try different dates: current day, past days, future days with menu and future days without menu
Try for different canteens
Verify the ticket refers the selected date and canteen
Acceptance tests for US2.1a Valid ticket (validate ticket)
Try different usernames, including invalid ones
Try a username with zero, one, two and more unused tickets for current day
Try a username with one or more unused tickets for current day / next days
Verify the ticket was correctly validated (checked as used)

[Back Home](https://bitbucket.org/ws-18861-19256-19377/repo_18861_19256_19337/wiki/Home)