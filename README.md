# prisma-middleware-lambda-environments

## Idea

Use a Prisma middleware to send information about the Lambda environment to an "endpoint" (can be whatever) so the user can understand how many different Lambda environments are currently interacting with their database, how many connections are open on each, how many queries are executed via them. Sould run in the background and not influence the actual app runtime negatively optimally.

