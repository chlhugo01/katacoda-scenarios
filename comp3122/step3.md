
Show menu
`curl "https://[[HOST_SUBDOMAIN]]-15000-[[KATACODA_HOST]].environments.katacoda.com/menu"`{{execute}}

Show menu of first restaurant
`curl "https://[[HOST_SUBDOMAIN]]-15000-[[KATACODA_HOST]].environments.katacoda.com/menu/1"`{{execute}}

Add food of first restaurant 
`curl "http://localhost:15000/menu/1?food_name=fooda&food_price=14" -X POST`{{execute}}

Delete spcified food of first restaurant 
`curl "http://localhost:15000/menu/1?food_name=fooda&food_price=14" -X DELETE`{{execute}}
