# Trigger-Notes
Learning Trigger

# Things could be done with APEX Trigger

1. Send Email
2. Create any other records
3. Doing a callout (Integration)
4. Delete any other record
5. Update any records (related/non related)
6. Prepopulate the record that got inserted/updated
7. Fire an error (If record not matching a criteria)
8. and Many more complex scenarios

# Where Apex is not necessary

When Workflow rules, Process Builder, Flows, Validation rules  and  Duplicate rules can do the job, APEX is not reuired.

#Trigger Events

Trigger logic can be called in below events

1. Before Insert
2. AfterInsert
3. Before Update
4. After Update
5. Before Delete
6. After Delete
7. After Undelete

# Order of Execution

Before Insert(Flow) -> Before Insert(APEX Trigger) -> Insert -> After Insert(APEX Trigger) -> Workflows -> Process Builder -> After Insert (Flow) -> Commit
