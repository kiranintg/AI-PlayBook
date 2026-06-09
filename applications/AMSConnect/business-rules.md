# XYZ Messenger - Business Rules

## Messaging Rules

### Peer-to-Peer Messaging

* Doctors can send messages to doctors.
* Doctors can send messages to patients.
* Patients can send messages to doctors.

### Broadcast Messaging

* Authorized users can send broadcast messages.
* Broadcast messages can target multiple recipients.

### Pager Messaging

* Basic Users are pager users.
* Pager users cannot reply to pager messages.

### Service Team Messaging

* Messages can be sent to service teams.
* Team members receive the message.

### Recurring Messaging

* Messages can be scheduled.
* Messages can recur based on configured frequency.

## User Permissions

### Super Admin

* Full access

### Admin

* Institute-level administration

### Prime User

* Full messaging capabilities

### Basic User

* Limited messaging capabilities

## Notification Rules

* Notifications should be generated when messages are received.
* Notification failures should be logged.

## Audit Rules

* Message creation should be logged.
* Message updates should be logged.
* Message delivery events should be logged.
