# MEAN Stack Deployment Exercise

## Exercise Overview

This exercise consists of deploying a three-tier application with the following components:

- **Frontend**: Angular 6 application
- **Backend**: Node.js API server  
- **Database**: MongoDB

## Architecture Requirements

### Must-Have Requirements

1. **Dockerization**: Both frontend and backend must be containerized
2. **Internet Exposure**: Frontend must be accessible from the internet
3. **Load Balancer**: Frontend must be exposed via a load balancer
4. **High Availability**: Solution must provide high availability
5. **Cost Effectiveness**: Solution should be cost-effective

### Nice-to-Have Requirements (Optional)

1. **Security**: Backend and database should not be directly reachable from internet
2. **Custom Domain**: Application endpoint should use a custom DNS (not load balancer IP)
3. **HTTPS**: Connection should use HTTPS with valid certificate (consider ACM)
4. **Container Orchestration**: Deploy using Docker orchestration tools:
   - AWS ECS (EC2 or Fargate)
   - Kubernetes
   - Docker Swarm
   - Docker Compose

## Repository Information

### Frontend Repository
- **URL**: https://github.com/dram2093/MEAN-Stack-User-Registration-Front-End
- **Technology**: Angular 6
- **Port**: 4200 (development)
- **Build**: `ng build --prod`

### Backend Repository  
- **URL**: https://github.com/dram2093/MEAN-Stack-User-Registration-Back-End
- **Technology**: Node.js + Express.js
- **Port**: 3000 (development)
- **API Endpoint**: `/api/register`

### Database
- **Technology**: MongoDB
- **Connection**: Configure via environment variables

## Exercise Guidelines

### What We Expect

- You will be asked to do a walkthrough of your complete solution
- We may ask questions and present scenarios that require changes to be made during the live session
- Use your best judgment in implementing the requirements
- Feel free to ask questions if you have any

### Deliverables

1. **Working Application**: Fully deployed and accessible
2. **Architecture Documentation**: Explain your solution approach
3. **Cost Analysis**: Provide estimated costs for your solution
4. **Security Implementation**: Describe security measures taken
5. **Monitoring Setup**: Show how you would monitor the application

### Success Criteria

Your solution will be evaluated based on:

- Meeting all must-have requirements
- Implementation of nice-to-have requirements (bonus points)
- Architecture decisions and justifications
- Cost optimization strategies
- Security best practices
- Ability to handle questions and modifications during the session

## Questions to Consider

- How would you handle increased traffic?
- What if the database goes down?
- How would you implement CI/CD?
- What about disaster recovery?
- How would you optimize costs further?

## Support

Don't hesitate to reach out if you have any questions. Use your best judgment and be ready to explain your decisions during the live session.

Good luck!