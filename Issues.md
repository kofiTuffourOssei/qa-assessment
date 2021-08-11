# Title: Incorrect items/task left number

## Severity: 

Low 

## Description: 

The ALL pane displays  only sum of the  active task which instead should have displayed the sum of all active and completed task or items. When User clicks on ALL button 3 items left, instead of 4 items/task.

## Steps to reproduce

1. User launches todo Application
2. User creates " wash clothes ".
3. User creates " get suitcase from garage ".
4. User creates " pack clothes "
5. User creates " check in for flight "
6. User completes " wash clothes "

## Proposed Solution:

Expected behavior: Irrespective of the items/tasks completed or active, items in ALL  pane must display summation of active and completed task/items.



# Title: Application navigates to Wrong pane  

## Severity: 

Medium

##Description:

When user creates task/items, and the user proceeds to complete the task. When the User clicks on completed to delete/clear completed task. User is navigated to ALL which in-turn displays only active task/items.

## Steps to Reproduce

1. User launches Application
2. User creates "Wash clothes"
3. User creates "get suitcase from garage"
4. User creates "pack clothes"
5. User completes "wash clothes"
6. User clicks clear completed.

## Proposed Solution

Expected behavior : User clicks clear completed, user must be navigated to completed. Then User can clear or deleted completed task/items.



# Title: Items left unchanged after user selects completed

## Severity: 

Low

## Description: 

When user creates tasks/items and proceeds to complete task.User clicks completed, the number of items left must also change to correspond to items/task completed.

## Steps to Reproduce

1. User launches todo Application
2. User creates "wash clothes"
3. User creates "get suitcase from garage"
4. User creates "pack clothes"
5. User completes "wash clothes"
6. User completes "get suitcase from garage"
7. User clicks completed

## Proposed Solution

Expected behavior: When user clicks on completed, items left must display only completed task.



# Title: Dropdown displays completed items in ALL menu

## Severity: 

Medium

## Description:

After user has created tasks and completed the task. When the user clicks on the dropdown, the dropdown navigates the user to ALL which only displays completed task.

## Steps to Reproduce

1. User launches todo Application
2. User creates "wash clothes"
3. User creates "get suitcase from garage"
4. User creates "pack clothes"
5. User completes "wash clothes"
6. User clicks on dropdown

## Proposed Solution

Expected behavior: When user clicks on the dropdown, the dropdown must display ALL tasks not only completed task



# Title: Incorrect items left when user clicks dropdown

## Severity: 

Low

## Description:

When user clicks dropdown , user is navigated to ALL pane. The items/tasks left displays zero.

## Steps to Reproduce

1. User launches todo Application
2. User creates "wash clothes"
3. User creates "get suitcase from garage"
4. User completes "wash clothes"
5. User clicks dropdown

## Proposed Solution

When user clicks dropdown, it must navigate to ALL ,which must display all items.



## Instructions on how to test two of the solutions:

1. Test suite is prepared for retesting for the failed modules.
2. Good test cases are applied to the todo Application module.
3. The actual result is then compared to expected output of the test case.
4. Retesting is applied to the defective modules ,until bugs are fixed.
5. After fixing the bugs, retesting can be performed on the todo Application to assert that all bugs are absent.

