
# AMS connect - Application Context

## Application Overview

### Name

AMS connect Messanger

### Purpose

Secure communication platform for healthcare institutions, doctors, service teams, and patients.

### Criticality

HIGH

### Business Impact

Failure in message delivery can result in communication breakdown between doctors, patients, and healthcare institutions, potentially impacting patient care.

---

## User Roles

### Super Admin

* Full system access
* Manage institutes
* Manage users
* Configure permissions
* Access reports

### Admin

* Manage users within assigned institute
* View reports
* Manage permissions

### Prime User

* Send and receive messages
* Create broadcasts
* Create recurring messages
* Participate in service teams

### Basic User (Pager User)

* Receive pager messages
* Limited messaging capabilities
* Cannot reply to pager messages

---

## Modules

### Login

* Authentication
* Authorization
* Session Management

### Messenger

* Peer-to-Peer Messaging
* Broadcast Messaging
* Pager Messaging
* Service Team Messaging
* Recurring Messaging

### Profile Settings

* User preferences
* Notification settings

### Admin

* User administration
* Role management

### User Management

* Create User
* Edit User
* Deactivate User

### Notifications

* Message alerts
* System notifications

### Institute

* Institute management
* Institute configuration

### Reports

* Usage reports
* Message reports
* Audit reports

### Permissions

* Role-based access control
* Feature access management

---

## Message Types

1. Doctor to Doctor
2. Doctor to Patient
3. Patient to Doctor
4. Service Team Messaging
5. Broadcast Messaging
6. Pager Messaging

---

## High-Risk Areas

1. Message Delivery
2. Notification Delivery
3. User Permissions
4. Audit Logging
5. Message Scheduling
6. Recurring Messaging
7. Service Team Communication
8. Patient Communication

---

## Testing Priorities

### Critical

* Message Delivery
* Notification Generation
* Permissions
* Authentication
* Recurring Messaging

### High

* Reporting
* Audit Logs
* User Management

### Medium

* Profile Settings
* Preferences
