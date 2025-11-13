## what is the CloudTrail
AWS CloudTrail is an AWS service that helps you enable operational and risk auditing, governance, and compliance of your AWS account. Actions taken by a user, role, or an AWS service are recorded as events in CloudTrail. Events include actions taken in the AWS Management Console, AWS Command Line Interface, and AWS SDKs and APIs

## How it works
Event recording: CloudTrail records actions taken within your AWS account as events.
Log delivery: Events are logged and can be sent to an Amazon S3 bucket for long-term storage and analysis.
Event history: A basic, searchable history of management events is available for the past 90 days in each AWS region without extra charges.
Event categories:
Management events: Record control plane operations like creating or deleting an S3 bucket.
Data events: Record data plane actions, such as reading or writing an S3 object.
Insights events: Analyze management events to identify and alert on unusual API activity, which can incur additional charges. 
## Key features
`Auditing and compliance`: Helps monitor and audit user activity to ensure compliance with rules and regulations.
Security analysis: Assists in investigating security incidents by tracking changes and identifying who made them.
Troubleshooting: Provides a detailed history of API calls for operational troubleshooting.
Resource change tracking: Tracks the history of an AWS resource from creation to deletion.
Multi-Region support: You can create a "multi-Region trail" to capture activity across all enabled regions in your account.
Integration: Can be integrated with other services like CloudWatch and EventBridge for alerts and notifications. 
