# Hosting a Full-Stack Application

## Udagram api url

[backend](http://udagram-api-dev222222222222222222.us-east-1.elasticbeanstalk.com)

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

## Udagram back end

[frontend](http://myawsbucket589745.s3-website-us-east-1.amazonaws.com)

## CircleCi

[CircleCi](https://app.circleci.com/pipelines/github/M0stafa123/udagram)

## bucket

![bucket](https://user-images.githubusercontent.com/98834672/216066108-5ed85b7c-f10c-4b60-95fd-1e4b8166179e.PNG)

## ebs configuration

![ebs-config](https://user-images.githubusercontent.com/98834672/216066227-f7f4d2c9-846a-4df6-b36a-052680275367.PNG)

## ebs status

![ebs](https://user-images.githubusercontent.com/98834672/216066259-901fd240-2374-499a-95a0-6f08d66b82b5.PNG)

## rds status

![rds](https://user-images.githubusercontent.com/98834672/216066902-c55f8b64-658a-4a2a-ae3c-6ea931def5fe.PNG)

## static wep

![url](https://user-images.githubusercontent.com/98834672/216066333-98b29061-0060-4aba-814f-2c4bd69472c6.PNG)

## the app

![app](https://user-images.githubusercontent.com/98834672/216067912-2b1529b8-7f65-4f5d-b1fa-5bcd507d5b6c.PNG)

## architecture

![architecture](https://user-images.githubusercontent.com/98834672/216074232-48e9518b-7429-40f3-833f-b7d8c066661f.png)

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. <Place holder for link to classroom article>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <Place holder for tlink to classroom article>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
