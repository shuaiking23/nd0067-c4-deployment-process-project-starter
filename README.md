# Hosting a Full-Stack Application

This is a fork of the project starter from [https://github.com/udacity/nd0067-c4-deployment-process-project-starter](https://github.com/udacity/nd0067-c4-deployment-process-project-starter) provided for illustrating CI/CD.

# Udagram

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.



### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Installation


CircleCI is used to manage piping for code build and deployment.

Frontend site is accessible via [http://udacity-20230410.s3-website-us-east-1.amazonaws.com](http://udacity-20230410.s3-website-us-east-1.amazonaws.com)

API is hosted at [http://udagramapi-env.eba-6x2icvnm.us-east-1.elasticbeanstalk.com/](http://udagramapi-env.eba-6x2icvnm.us-east-1.elasticbeanstalk.com/)

### Screenshots

![circleci](https://github.com/shuaiking23/nd0067-c4-deployment-process-project-starter/blob/master/documentation/screenshots/circleci.png?raw=true)
![circleci_env](https://github.com/shuaiking23/nd0067-c4-deployment-process-project-starter/blob/master/documentation/screenshots/circleci_env.png?raw=true)
![EB_health](https://github.com/shuaiking23/nd0067-c4-deployment-process-project-starter/blob/master/documentation/screenshots/EB_health.png?raw=true)
![S3_buckets](https://github.com/shuaiking23/nd0067-c4-deployment-process-project-starter/blob/master/documentation/screenshots/S3_buckets.png?raw=true)


## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
