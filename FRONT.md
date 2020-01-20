# Front
## Technology
React

## Design
https://www.figma.com/file/AEBM97yzW6IbdET6MD3YoI/Untitled?node-id=0%3A1

## Goals
The platform should help us to comminicate in a constructive, honest and positive way.
We must be able to create thread (posts), to answer with messages, 

## Userland
###### createUser
###### getCategories
###### getThreads/categoryId
###### getMessages/threadId
###### createThread
- categoryId
- title
- message

###### createSource
- threadId

###### createMessage
- can answer to thread AND any message
- when answering to a message, it creates a new thread in the database with ratings etc...
- threadId
- sources url[]

###### createSource
- add a source to a thread / message

###### getSources/threadId

###### createAnnotation  
Select a sentence in a message and create a new thread from it
- messageId
- content


###### createRating
- for messages, posts, source

addSource
getSources

## ModLand
flagUser