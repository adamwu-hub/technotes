# AWS ALB vs AWS API Gateway

* ALB can only create listener by Protocol:Port pair (such as https:443) and forward to a Target Group (can be a Lambda function)
* APIGW can integrate with HTTP/REST/Websocket protocol and based on HTTP method and route
* APIGW can integrate with authoriser, can have API key, mTLS, ALB doesn't
* APIGW has builtin dashboard and resource policy, ALB doesn't
