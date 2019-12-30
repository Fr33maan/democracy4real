# Back
## Technology
[strapi](https://strapi.io/)
postgres

## Database structure\
### theme
name
slug
message_id

### post
thread_id
message_id
name

### message
post_id

### thread_rating
thread_id

### post_rating
post_id

### message_rating
message_id
user_id
sincerity - INTEGER (0 to 100)
hypocrysy - INTEGER (0 to 100)
calmness
wiseness
correctly_sourced
argumentary quality
anger
manipulative
truth
listening
empathetic
objective

### message_source
**Message sources in order to increase 'correctly_sourced' rating**
message_id
url

### source_rating
fiability - INTEGER (0 to 100)
accuracy - INTEGER (0 to 100)
known_source - INTEGER (0 to 100)

### user
username
password
role

## Modules
auth
rest CRUD API for above tables with role access
roles ( admin, mod, user )

## CI / CD
integration tests (superagent)
functionnal tests of API