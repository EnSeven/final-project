# EnSeven Final Project

## Overview
A multi-workspace, multi-room messaging application

## Features
* TBD

## Back-End
* Socket.io Server
* DB for Persistence: AWS Dynamo with Dynamoose ORM
* Deployment Option 1: Express App on EC2 (auto-deployed)
* Deployment Option 2: Serverless app with Lambda ([Good Debate and Links Here](https://stackoverflow.com/questions/33926619/is-it-possible-to-use-socket-io-with-aws-lambda))

## Desktop App
* React Application
* Socket.io Client
* Deployed to AWS Cloudfront

## Mobile App
* Socket.io Client
* React Native Client

### Teams
1. UI - Will buld both the React Desktop and the React Native apps in tandem
1. Chat Backend - Will build out the Socket.io Server either as an express app to be deployed to EC2 as a Lambda Function
1. API Backend - Will build out the Dynamo DB at AWS and either API Gateways + Lambda or an express app at EC2
1. Dev Ops - Will make sure that all of the AWS deployments are happening and assist the other teams on wiring
