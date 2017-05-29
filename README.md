# my-social-network
Social network made with &lt;3
 - Relations (1:1) will be used Redis
 - Relations (n:n) will be used Neo4j
 - Documents will be stored using MongoDB


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
  - Birthday

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

## Video 
  - Video id

## Tag
  - Tag id
  - Tag name

## Like 
  - Like id
  - User id // 'Cause only one user can "own" the like
  - Post id
