
# Core Features - Backend

## Authentication

- What kind of auth do we want?
	- Email/Phone#/OAuth
- Role Management
	- admins, users, restaurant owners, verified reviewers


### Auth Types

| Authentication Method                | Present in App? |
| ------------------------------------ | --------------- |
| Email / Password                     | ✅❌              |
| Phone # / Password                   |                 |
| Phone # / Verification Code (TikTok) |                 |
| Google                               |                 |
| Facebook                             |                 |
| Instagram                            |                 |
| TikTok                               |                 |
| SSO                                  |                 |

### Role  Management

| Roles                 | Present in App | Scope                        |
| --------------------- | -------------- | ---------------------------- |
| Super Admin           |                | Full Access to everything    |
| Admin                 |                | Can manage users/data        |
| Owner                 |                | Manages the restaurant       |
| Creator/Verified User |                | Potentially special features |
| User                  |                | Normal User                  |

## Database

- SQL or NoSQL?
- What kind of queries do we expect to be running?
- Any analytics?
- Any AI?
- What models do we want to have?
	- Users/Post(Review)/Restaurant/Comments/Likes

### SQL vs NoSQL


### Queries we are expecting


### Analytics


### AI in the App


### Data Models


## Media Handling

- There will be lots of images.  How will we store them?
- Will we allow video?
- Will we permanently be storing these?  
	- Potential account deprecation

### Video?


### Media Storage Options


### Storage Periods


## Notifications

- Do we need any notifications?
- How will we send them if so?
	- App/Text/Email
- What will warrant a notification?

## Will we need notifications


### Notification Method


### When to send notifications


## Searching and Filtering

- How are users able to search?
	- NLP/Keyword/Location/FoodTypes/Restaurant
- Do we want to add in filtering?

### Search Options


### Filtering
