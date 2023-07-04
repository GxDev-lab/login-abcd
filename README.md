# login-abcd
login abcd


lrxvgjbbzhxpgfdazy@bbitf.com



domain
1203956624712899


FeedbackApp

client id = 1204956953756324

Client secret
2e711af79a3817180175d3b6e83107f6



project id = 1204956581962734


https://github.com/mackerelsky/asanataskexporter/blob/master/Asana_Exporter/Program.cs


```
curl 'https://app.asana.com/api/1.0/projects/1204956581962734/tasks?limit=10'   -H 'Accept-Language: en-US,en;q=0.9'   -H 'Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJhdXRob3JpemF0aW9uIjoxMjA0OTU3NDUzNDU4NjEwLCJzY29wZSI6ImRlZmF1bHQgaWRlbnRpdHkiLCJzdWIiOjEyMDQ5NDgxMjM0NTgxMDMsImlhdCI6MTY4ODQwOTUxOCwiZXhwIjoxNjg4NDEzMTE4fQ.GpL8pAVsetXRxVic2N3Gg5aGTJqKn2hy7H7fUHwrI3k'   --compressed --insecure


eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJhdXRob3JpemF0aW9uIjoxMjA0OTU3NDUzNDU4NjEwLCJzY29wZSI6ImRlZmF1bHQgaWRlbnRpdHkiLCJzdWIiOjEyMDQ5NDgxMjM0NTgxMDMsImlhdCI6MTY4ODQxOTc5MywiZXhwIjoxNjg4NDIzMzkzfQ.cX51j4ssMFG9yCA2dMIbNnQKXZgxcSyaYygDo5WeGjU



    {
      "gid": "1204847550988224",
      "name": "Rocky",
      "resource_type": "user"
    },
    {
      "gid": "1204850544954006",
      "name": "John",
      "resource_type": "user"
    },
    {
      "gid": "1204876280887036",

```


## Auth end point details

https://developers.asana.com/docs/oauth


## code grant

There is no way to exchange access tokens for refresh tokens, because access tokens are intended to be a less secure credential than refresh tokens. I should also add that subsequent redirects to the implicit grant endpoint, once the user has authorized your app, shouldn't require the user to click through again. This is the correct way to handle auth on the client: you can't use refresh tokens without your Asana API client secret, which you don't want on your client. If you need long-lived tokens on the server, then you should use an authorization code grant on the backend. – 



https://stackoverflow.com/questions/39246941/can-i-use-asana-access-token-in-the-backend


https://developers.asana.com/docs/oauth

https://oauth.net/2/grant-types/authorization-code/


https://www.youtube.com/watch?v=guvhHTyyAUo





