#### Deploying to AWS Lambda with Serverless + GitHub Actions (Modern CI/CD)  
- [VideoLink](https://www.youtube.com/watch?v=oFYFqOzJdqY&list=PLhcs-OoRV25WGtgf7LYPJtfIK0fg6QX1D&index=3)
- Create username `lambda-user`create group `lambda-group` with full access `lambda, iam, cloudwathlog, s3,lambdarole, cloudformation, ssm` generate Acesskey and SecretKey.
- Create a github Repo and add the credentials (settings-security- secrets and vriables -Actions) click on **new repo secrets** add as `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY`.
#### Setting Up Serverless Framework With AWS
- Create a directory and install serverless
```
npm install -g serverless@3
serverless --version
serverless create --template aws-nodejs
```
- This will create **handler.js, serverless.yml and .gitignore**
- create `src` folder and move handler.js file.