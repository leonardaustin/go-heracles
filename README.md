# Go Heracles (Auth Service)
*Gatekeeper of Olympus (a.k.a. Auth Service)*

Authenticate users with email and password over public endpoint. Return a token valid for a period of time (sent in request with validation range set in go config).

## Schema
*user*
- id (md5 of email address)
- email
- password
- first name
- last name
- type
- status
- created
- lastUpdated

*token*
- id
- userId
- userType
- created
- expire


