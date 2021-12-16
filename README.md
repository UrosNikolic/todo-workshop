# todo-workshop


## deploying

```
npm run sls -- deploy
```

## creating new user with aws cli

```
aws cognito-idp --region eu-central-1 sign-up --client-id <YOUR-CLIENT-ID>  --username <YOUR-EMAIL> --password <YOUR_PASS> --user-attributes Name=name,Value=<YOUR-NAME>
```