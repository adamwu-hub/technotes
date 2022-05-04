# AWS ALB vs AWS API Gateway

* ALB can only create listener by [Protocol:Port pair (such as https:443)](https://s3.ap-southeast-2.amazonaws.com/elb-polaris-static-content-ap-southeast-2-prod/2022-04-27T13-59-17_1654e9efefba4b5857d808df24f96ad3285a6ad1214a86c8bc7678d16430da54/Static/ALBdiagramwcallouts.svg) and forward to a Target Group (can be a Lambda function)
* APIGW can integrate with HTTP/REST/Websocket protocol and act based on HTTP method and route
* APIGW can integrate with authoriser, can have API key, mTLS, ALB doesn't
* APIGW has builtin dashboard and resource policy, ALB doesn't
