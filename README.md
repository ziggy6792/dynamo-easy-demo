# dynamo-easy demo

This project serves as a showcase how dynamo-easy can be used.

Imagine a system where every employee of a company logs his work time per project with a start time and duration.
We use three models each with its table

- Project

- Employee

- TimeEntries

There are services one for each model to execute different operations on the tables.
There are also some write operation though we do not allow these for security reasons.
  
## credentials / security
This demo uses an aws-iam user with read access to those 3 tables only which means no write operations will succeed.
It's meant for you to clone the project and play around with it.

## infrastructure
see infrastructure.yml for the essential resource definition
