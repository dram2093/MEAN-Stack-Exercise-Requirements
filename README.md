# MEAN Stack Deployment Exercise

The test will consist on deploying a three tier app, front end, back end, and database. The front end is an Angular6 app, the back end a NodeJS app, and the database engine is MongoDB.

## Repositories

- **Front end**: https://github.com/dram2093/MEAN-Stack-User-Registration-Front-End
- **Back end**: https://github.com/dram2093/MEAN-Stack-User-Registration-Back-End

## Requirements

### Must-Have

1. The front end and backend need to be Dockerized.
2. The front end needs to be Internet exposed.
3. The front end needs to be exposed via a load balancer.
4. "High Availability" is required.
5. The solution should be cost effective.

### Nice to Have (optional)

1. The back end and database shouldn't be reachable from Internet.
2. The app endpoint shouldn't be the load balancer DNS or an IP, needs to be a DNS (if you have the ability to provide one).
3. The connection needs to be through HTTPS with a valid certificate (consider using ACM) (if you have a DNS).
4. The apps need to be deployed on a Docker containers orchestration tool ECS (whether with EC2 nodes or Fargate), or any other similar tool (Kubernetes, Docker Swarm, even Docker Compose, etc).

## Instructions

Please, be ready to do a walkthrough of the whole solution. We will ask some questions and probably present a situation that will require changes to the solution that need to happen in the live session. Don't hesitate to reach us if you have any questions. Use your best judgement!

We recommend using AWS for this exercise, but you are free to choose the cloud provider and tools that you think are best for the solution.

Finally, don't hesitate to ask questions if any.
