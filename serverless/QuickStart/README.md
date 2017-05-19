### Usage

```
npm install -g serverless

serverless create --template aws-nodejs --path my-service

cd my-service

npm install

serverless deploy -v

serverless deploy function -f hello

serverless invoke -f hello -l

serverless logs -f hello -t

serverless remove
```
