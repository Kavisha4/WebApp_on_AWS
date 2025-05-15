# WebApp_on_AWS
Used AWS Amplify, IAM, Lambda, DynamoDB and API Gateway
<img width="1291" alt="image" src="https://github.com/user-attachments/assets/2d7cde21-3114-4de3-afb0-86034b545d7a" />

# Creating a web app on AWS

Link to website : https://dev.d2zaifoypgoa7r.amplifyapp.com/

1. Amplify to host webpages
2. I have hosted the webpage - https://dev.d2zaifoypgoa7r.amplifyapp.com/
3. Lambda function is a piece of code that runs serverlessly when triggered
4. So now after creating the lambda function which takes base and power we need to use an API Gateway to connect aplify and the lambda function 
5. API Gateway- use websockets ,rest, apl
6. So we create a REST API and make a post method for our lambda function, we then do cross over and enable CORS, we then deploy the API and get the URL https://x0qc4qoc9j.execute-api.us-east-1.amazonaws.com/dev
7. So now we need to store the Math results so to use that NoSQL-DynamoDB(key-value)
8. We set up permissions IAM, we need to give lambda function to write in the database

9. <img width="511" alt="image" src="https://github.com/user-attachments/assets/90276dac-4af1-4477-8c88-b98f0690bf18" />

