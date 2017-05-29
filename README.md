# my-social-network
Social network made with &lt;3

For the architecture:
 - For Relations (1:1) Redis
 - For Relations (n:n) Neo4j
 - Documents using MongoDB
 - Real time with WebRTC when available, otherwhise WebSockets
 - Public and static content with nginx
 - Views with pug 
 - server requests with koajs
 
# Models

## User
  - User id
  - Username
  - Profile Photo id
  - Interested in 

## User status
  - User status id
  - Status
  - Relationship status
  
## User info 
  - User info id
  - First Name
  - Middle Name
  - Last Name
	
## User Birthday
	- User Birthday id
	- Day
	- Month
	- Year

## Chat Group
  - Chat Group id

## Message 
  - Message id
  - Message content

## Post
  - Post id
  - Text content
  
## Photo 
  - Photo id
	- Photo LQ url 
	- Photo HQ url

## Video 
  - Video id
	- video LQ url
	- video HQ url

## Tag
  - Tag id
  - Tag name

## Like 
  - Like id
  - User id // 'Cause only one user can "own" the like
  - Post id
