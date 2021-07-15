# MEAN-MongoDB_Express_Angular_Node.js-Project

1.MongoDB:
  create database: Task Manager
  create collections:List,Task,User
  
  
2.API
  Basic:POST,PATCH,GET,DELETE
  
  
  
3.Frontend
  Angular + Bulma(css framework)
  
  
  
  
  *******
using **JSON web tokens(JWT)** to authenticate users (JSON Wen Tokens are an implementation of  cryptographic verification system which is stateless and that means don't need to query the database or any data store to verify the user this means that the API can response a request much faster)

JWT contains a data payload so that when the API verifies the user, use the information in  data payload. object will be signed using a secret string that stored on the server

pro: revoke access on some devices  ⇒ **Refresh tokens (Session Token)** delete the fresh token from the database when want to revoke access and therefore that refresh token can no longer generate new access tokens
