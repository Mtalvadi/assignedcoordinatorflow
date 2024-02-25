# Task - Change Owner to Assigned Coordinator

## Use Case : Based on the picklist value in “Assigned Coordinator” custom fields on Task object,  “Assigned To” field should be updated to the user with the same name as in the picklist value.

![image](https://github.com/Mtalvadi/assignedcoordinatorflow/assets/83495051/cc1297f0-ab0d-4f87-bf5f-68a2fc212b0c)

## Pre-requisite :

-	Custom field named - “Assigned Coordinator” of picklist data type is created on the Task object (in the terms of backend, all the configuration related to Task are done on the Activity object).
-	Two users are created to test the automation. Here, the users named as - “Bob Apples” & “Tina Apples” are created.
-	Picklist values in the Assigned Coordinator field will contain the exact same value as the user created. Here, Bob Apples & Tina Apples are two picklist values in the Assigned Coordinator field.
-	Record triggered type (Task - Change Owner to Assigned Coordinator) flow is configured and activated.

## Solution/Automation : 

1. After 2 users & exact same picklist values are created in the Assigned Coordinator field, Go to any account and create a new task under Activity tab.

![image](https://github.com/Mtalvadi/assignedcoordinatorflow/assets/83495051/fba5149e-d7a7-4290-8463-53fb7c842c89)

2. While creating the task, make sure the Assigned To field value is different than the 2 users we have created to test this automation.

![image](https://github.com/Mtalvadi/assignedcoordinatorflow/assets/83495051/47c4228d-05da-4817-a1ef-a3094dcee7cb)

3. After task is created, update the Assigned Coordinator field value to either of the users created.

![image](https://github.com/Mtalvadi/assignedcoordinatorflow/assets/83495051/23745747-d5bd-41c6-a83c-313744865c7e)

4. Once updated, you will see that the “Assigned To” value would be updated exactly to the “Assigned Coordinator” value.

![image](https://github.com/Mtalvadi/assignedcoordinatorflow/assets/83495051/8946cc2e-a479-4fdf-b76c-5aa948e858c8)
