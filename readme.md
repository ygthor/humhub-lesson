Need to enable  Restful API and 


to get bearer
Method POST
http://humhub.test/api/v1/auth/login?username=admin&password=admin123

if success:
```
{
    "code": 200,
    "message": "Success",
    "auth_token": "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzUxMiJ9.eyJpYXQiOjE2MTUwODU3NTIsImlzcyI6Imh0dHA6XC9cL2N1c3ZlbnQuY29tXC9zY29sZGVtb2h1YiIsIm5iZiI6MTYxNTA4NTc1MiwidWlkIjoxLCJlbWFpbCI6ImdvbmxleV85OUBob3RtYWlsLmNvbSJ9.6bSE0yPPYj0FDU4O5uIMJqzS6g-1qpr28gsnbUUAURvJkK8j3-_Is8CSvipUXKf70PpxOnSqeMyPxjWKmqhB6Q",
    "expired_at": 0
}
```
the auth_token is bearer token


to get post content
Method GET
http://humhub.test/api/v1/post/POST_ID

HEADER Example
Content-Type: application/json
Authorization: Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzUxMiJ9.eyJpYXQiOjE2MTQ2MTY5ODUsImlzcyI6Imh0dHA6XC9cL2h1bWh1Yi50ZXN0IiwibmJmIjoxNjE0NjE2OTg1LCJ1aWQiOjEsImVtYWlsIjoiYWRtaW5AYWRtaW4uY29tIn0.ufMEtDbkvWALRUaJG0IKcGGFAyB3at9q63fu4L1ALK9qb2nmFlkilXefAa6Sd_Z1yKpvaqh6gc_n9fxUMOoLBw
