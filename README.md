# JWT

To help prepare for API authentication tomorrow, research [JSON Web Tokens](https://jwt.io) (known as JWTs). This should take about 30 minutes. Answer the following questions and submit this README as your homework:

1. What are the 3 parts of a JWT? Header, Payload and Signature - all accessed via the ID token.
2. What information does each part contain? Payload is the user's data which is often sensitive. Header lists the token type which is JWT and also the algorithm. The signature is created based on the all the other parts and that is how one can be assured that no data was changed/tampered during transmission. 
3. Why do people use JWTs for authentication? A great resource to read would be https://jwt.io/introduction/. Because they keep the user's payload data secure since only the user and the JWT have the secret which is the key to the info.
