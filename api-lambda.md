## Data ingestion in Sql Rds with AWS Api Gateway

**Description:** The client performs a Post call to Api Gateway with a body to store. The authorization is granted using the Lambda Authorizer. If the user is granted access, the Api Gateway triggers the Lambda and forwards the body. The Lambda process the call then stores it to a Rds table. The Rds credentials are retrieved by Lambda from Aws Secret Manager.

<img src="images/api-lambda.png?raw=true"/>