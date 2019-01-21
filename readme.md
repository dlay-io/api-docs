# Dlay.io REST API documentation

https://{domain}.dlay.io/api/v1/{resource}

## Authenticaton

## Tasks
### POST /v1/tasks
### PUT /v1/tasks/:id
### GET /v1/tasks?worker=manobi&status=retry&start=2016&end=2017
### GET /v1/tasks/:id
### GET /v1/tasks/:id/history
### DELETE /v1/tasks/:id

## Workers
### POST /v1/workers
### PUT /v1/workers/:id
### POST /v1/workers/:id/secrets

## Jobs
### GET /v1/users
### GET /v1/users/:id
### POST /v1/users
### PUT /v1/users/:id
### DELETE /v1/users/:id

## Users

# Accounts API
https://accounts.admin.dlay.io
https://dlay.io/plans
https://dlay.io/prices
https://dlay.io/prices


## Create
POST https://accounts.dlay.io
{
	domain: ‘manobi’
}
https://dlay.auth0.com/api/v2/


curl --request GET \
  --url https://dlay.auth0.com/api/v2/ \
  --header 'authorization: Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiIsImtpZCI6Ik9FUXdSVEk1TVVZek5qbEZRMFpCTkRneU16VkROVUUzUWpVMU56UkRORVkyTWtRd00wWTFNdyJ9.eyJpc3MiOiJodHRwczovL2RsYXkuYXV0aDAuY29tLyIsInN1YiI6ImZRaFZUN2JYQmFkdUJWNDJNTndJeUxGZU5oc1ZDWkNrQGNsaWVudHMiLCJhdWQiOiJodHRwczovL2RsYXkuYXV0aDAuY29tL2FwaS92Mi8iLCJpYXQiOjE1NDY0NDI2NjMsImV4cCI6MTU0NjUyOTA2MywiYXpwIjoiZlFoVlQ3YlhCYWR1QlY0Mk1Od0l5TEZlTmhzVkNaQ2siLCJndHkiOiJjbGllbnQtY3JlZGVudGlhbHMifQ.TI2g_WwR4P8uyJsLkvcV_BUjfM9wyNmPqObDlYyyBAmPDJ388QiYyegscnPbIOB7bwDpeOpnpL2irA3iNCYP4K9miF8fTe-ymWvzS6EaN1gIX3TyFhk1JT-t7YTQKCohGhYfr_KqHNRDa7kyLfBLpL5URIMQQ8CW1j_k55uPqpkmIlAL78RSl36CmRJxNp-HmL35VXDMrsG63L2Ans-73DI6x4IBYmAE2z10yXKRXaK8DPOCZOj_rMQxUP0m0AHPs2aySPhG4gKSlRYaoQaoZ8BaSLuyhrJEcG-EdzdridztY6grMS5RY5H-XeVwuk3JhY5prKXqszFUize5v8BtuQ'