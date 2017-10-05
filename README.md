# cloudformation_repo

This demonstrates using test kitchen to create cloud formation stacks as well as modify it via change sets.

kitchen create default-test -l debug

Create the stack if it does not exist and creates a change set if one is specified.

kitchen converge default-test -l debug

Executes the change set if one has been created
