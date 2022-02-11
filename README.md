     
# SpringBoot Application

A GitHub template to develop, preview, and deploy an Spring Boot application to AWS Elastic service in seconds.

## Why should you use this GitHub Template?
You can spin up your own Java + SpringBoot application in seconds. Deployment happens on an AWS Elastic BeanStalk Service.

The template also sets up a proper Github CI/CD environment.
Note: Once you create a repo out of this template, you can find your website deployed at your environment created in Beanstalk.

### What are the inputs to pass while setting up the template?
```
# Your AWS Access Key ID
- AWS_ACCESS_KEY_ID

# Your AWS Secret Key
- AWS_SECRET_ACCESS_KEY

# Your Region where ElasticBean environment is deployed
- AWS_REGION_CODE
```
---
#### How to get AWS Credentials? 🔑
Follow the step-by-step guide given on [AWS official doc](https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/getting-your-credentials.html)

- Note: You will have to create a BeanStalk deployment app in your AWS profile for the code deploymet to take place. This template will deploy the start code for application to your AWS BeanStalk. Checkout this [AWS Documentation](https://aws.amazon.com/elasticbeanstalk/) to learn more about creating AWS Elastic BeanStalk deployment.
---
### App hosted URL Link : ✈️
```
You could find the link to it here: 
Elastic Beanstalk >> Environments >> Springbootdeploy-env (your environment name)
```
---
### How to setup local development server?
```
to start a local development environment, and view in browser.
./gradlew bootRun
open http://localhost:8080/ 

# to run tests
./gradlew test

# to generate a production build
./gradlew build
```
---
### Learn more
- Spring boot <br>
     Visit [Spring](https://spring.io/guides) view the full documentation.

- AWS Cloud <br>
     Learn more about [AWS](https://aws.amazon.com/elasticbeanstalk/) from the official site.
---
### Contributors
- Atul Sharma (@Iltwats)
