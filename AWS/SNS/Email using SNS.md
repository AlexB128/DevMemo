# Sending emails using SNS
### Create Topic
<img src="../../files/SNS1/1.png" alt="position" />
<img src="../../files/SNS1/2.png" alt="position" />

### Create Subscription
<img src="../../files/SNS1/3.png" alt="position" />
<img src="../../files/SNS1/4.png" alt="position" />

### Confirm Subscription
<img src="../../files/SNS1/5.png" alt="position" />
<img src="../../files/SNS1/6.png" alt="position" />

### Lambda Function
```python
import boto3

def lambda_handler(event, context):
    client = boto3.client('sns')

    TOPIC_ARN = 'arn:aws:sns:XXXXXXXXXXXXXX:SendEmail'     
    msg = 'Message'
    subject = 'Subject'

    response = client.publish(
        TopicArn = TOPIC_ARN,
        Message = msg,
        Subject = subject
    )

    return response
```

<img src="../../files/SNS1/7.png" alt="position" />
