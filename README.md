## AWS Lambda SnapStart with X-Ray

This is a sample application to demonstrate using X-Ray with SnapStart enabled AWS Lambda function. You can find more details about this feature in [this]() blog post. 

The sample application is a simple Hello World application with the following architecture

![Hello World Application](images/Architecture.png)

### Deployment

#### Pre-requisites
1. AWS Account
2. Java 11
3. Maven
3. AWS [SAM CLI](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/install-sam-cli.html)

#### CLI Commands

`sam build`

`sam deploy -g`

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

