# gRPC-Framework

### Index

1. [Introduction](#introduction)

2. [Get Started](#get-started)

3. [Documentation](#documentation)

4. [Submit Issue](https://github.com/wohlig/wohligFramework/issues)

### 1. Introduction <a name="introduction"></a>

**gRPC Framework** can use used as Git Template for Projects related to microservices.

This is an Opinionated Framework which uses the following Technologies for the Microservices

1. [NodeJS](https://nodejs.org) - _16.0.0 or Above_

### 2. Get Started <a name="get-started"></a>

1. Create Git Repository using gRPC Framework as the Template. [Read More](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)

2. Make Sure you have NodeJS _16.0.0 or above_ installed on your local machine. [Read More](https://nodejs.org/en/)

3. Make Sure the Yarn _1.0.0 or above_ installed on your computer. [Read More ](https://yarnpkg.com)

4. Clone the Repository in your local machine. [Read More](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

5. Create **.env** file in your local Repository and add the following details content in the file. [Read More](https://www.npmjs.com/package/dotenv)

```shell
APP_ID=gRPC-Framework
PORT=50051
LOG_LEVEL=debug
```

6. Install the Dependencies for the framework using yarn

```shell
yarn install
```

7. Run the Application with Yarn

```shell
yarn start
```

Now your application will start

If Application Starts Properly you will find the following response

```shell
Server Started at Port 50051
```

8. As the application start, you will have create the Proto Files and test your gRPC service using Insomnia software. 

For reference, a snapshot of a smaple Test with Student.proto file in SayHello gRPC service is attached.

![gRPC](https://user-images.githubusercontent.com/97166046/172048911-cd46fd82-2490-4b5f-b41a-0252e463e1d6.PNG)

In Case you find issues please following the steps provided above or contact kushalwohlig@gmail.com

### 3. Submit Issue

Submit us on [Github Repository](https://github.com/wohlig/gRPC-Framework/issues)
