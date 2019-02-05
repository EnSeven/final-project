# Milestones

## Day 1 & 2
Begin / Complete the research on AWS services.

* Can we use API Gateway + Lambda + Dymamo to build out a simple API that lets us store and retrieve chat history?
* Can we use AWS Lambdas to do the socket.io server stuff?
* Failing both of those scenarios, what does launching to EC2 look like?
* By EOD we need an answer (i.e. some running code out there, with the beginnings of a process)
* Backend needs proof of life on their decision for both the API and the Socket Servers

Initial Deployment - Front-End

* One thing for certain is that our desktop will be deployed to Cloudfront. Use the api-tool to install a simple hello-world style react app to that service to get proof of life.
* Use John's [deployment tool](https://www.npmjs.com/package/@johnfellows/aws-tools ) and a simple `create-react-app` to get the app out there.
