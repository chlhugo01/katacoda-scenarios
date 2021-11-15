Login 

## Task
access https://[[HOST_SUBDOMAIN]]-15000-[[KATACODA_HOST]].environments.katacoda.com


Login the system as customer
`curl "https://[[HOST_SUBDOMAIN]]-15000-[[KATACODA_HOST]].environments.katacoda.com/login?username=Charlie&password=Charlie123" -X POST`{{execute}}

Login the system as restaurant
`curl "https://[[HOST_SUBDOMAIN]]-15000-[[KATACODA_HOST]].environments.katacoda.com/login?username=riley&password=Riley123" -X POST`{{execute}}

Login the system as delivery
`curl "https://[[HOST_SUBDOMAIN]]-15000-[[KATACODA_HOST]].environments.katacoda.com/login?username=Charlie&password=Charlie123" -X POST`{{execute}}

