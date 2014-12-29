# aws-elb-instance-runner

Run a command with the ip address of all instances in a elastic load balancer

## example
```
aws-elb-instance-runner my-elastic-load-balancer-DXZSR91UJMK4 echo
10.0.6.59
10.0.7.32
```

## Usage
you need to set the region in the environment variable: AWS_REGION, or configure this in ~/.aws/credentials. [offical docs](http://docs.aws.amazon.com/AWSJavaScriptSDK/guide/node-configuring.html)

```
Usage: aws-elb-instance-runner [elastic-load-balancer-id] [command]
```

## Use cases
This might be useful for writing deploy scripts.
