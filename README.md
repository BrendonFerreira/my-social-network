# my-social-network
Social network made with &lt;3 and microservices

For the architecture:
 - For Relations (1:1) Redis
 - For Relations (n:n) Neo4j
 - Documents using MongoDB
 - Real time with WebRTC when available, otherwhise WebSockets
 - Public and static content with nginx
 - Views with pug 
 - server requests with koajs
 
# Collections

## User
  - User id
  - Username
  - Interested in 

## User status
  - User status id
  - Status description
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

## Group
  - Group id
  - Name
  - Description
  - Created at

## Group main photo
  - Group main photo id
  - Group main photo LQ url 
  - Group main photo HQ url

## Group cover photo
  - Group cover photo id
  - Group cover photo LQ url 
  - Group cover photo HQ url

## Chat Group
  - Chat Group id
  - Chat theme
  - Chat group name

## Message 
  - id
  - content
  - type

## Message status
  - Message status id
  - Sent at
  - Received at
  - Readed at	

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

## Reaction 
  - reaction id
  - reaction type

# Relations

## User and profile photo
`User --- Photo id`

## User and message
`User id --< Message id`

## Group and message
`Group id --< Message id`

## User and User info
`User id --- User info `

## User and User info
`User id --- User info `
  
