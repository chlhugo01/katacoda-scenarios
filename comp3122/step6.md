Customer

new_order
`curl "https://[[HOST_SUBDOMAIN]]-15000-[[KATACODA_HOST]].environments.katacoda.com/order?order_id=4&user_id=1&restaurant_id=1&food_id=1&token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpZCI6Mi4wLCJncm91cCI6InJlc3RhdXJhbnQifQ.HPJABIfRF5vvUPGpNUGsQgFJSTH0bo4qhX8sAK0zoY4"`{{execute}}

Set order to prepared
`curl "https://[[HOST_SUBDOMAIN]]-15000-[[KATACODA_HOST]].environments.katacoda.com/order?order_id=4&token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpZCI6Mi4wLCJncm91cCI6InJlc3RhdXJhbnQifQ.HPJABIfRF5vvUPGpNUGsQgFJSTH0bo4qhX8sAK0zoY4&prepared=0`{{execute}}

Set order to shipped
`curl "http://localhost:15000/order?order_id=4&delivery_id=3&token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpZCI6Mi4wLCJncm91cCI6InJlc3RhdXJhbnQifQ.HPJABIfRF5vvUPGpNUGsQgFJSTH0bo4qhX8sAK0zoY4`{{execute}}