JWT authentication flow
1. Client Login

Username + Password

2. Authentication

Spring Security validates credentials

3. Generate JWT

Token signed with a secret/private key

4. Client sends JWT

Authorization: Bearer <token>

5. JWT Filter validates token

Signature, expiration, and claims

6. Access API

Valid token → authorized request