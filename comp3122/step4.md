Show menu
`curl "http://localhost:15000/order?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpZCI6MS4wLCJncm91cCI6ImN1c3RvbWVyIn0.9JKfBrotOmD2fPwVQHBpMFKvIfNtnJLhAH98fzwEK_Y&restaurant_id=1&food_id=1" -X POST`{{execute}}

Set order to prepared
`curl "http://localhost:15000/order?order=1&token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpZCI6Mi4wLCJncm91cCI6InJlc3RhdXJhbnQifQ.HPJABIfRF5vvUPGpNUGsQgFJSTH0bo4qhX8sAK0zoY4&prepared=true" -X PUT`{{execute}}

Add food of first restaurant 
`curl "http://localhost:15000/menu/1?food_name=fooda&food_price=14" -X POST`{{execute}}

Delete spcified food of first restaurant 
`curl "http://localhost:15000/menu/1?food_name=fooda&food_price=14" -X DELETE`{{execute}}

curl "http://localhost:15000/order?order=1&token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpZCI6Mi4wLCJncm91cCI6InJlc3RhdXJhbnQifQ.HPJABIfRF5vvUPGpNUGsQgFJSTH0bo4qhX8sAK0zoY4&prepared=true" \
  -X PUT