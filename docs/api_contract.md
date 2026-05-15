\# API Contract - User Profile



\*\*Endpoint:\*\* `/api/v1/profile`

\*\*Method:\*\* `GET`

\*\*Response Body (JSON):\*\*

{

"id": 1,

"username": "mahasiswa\_sd",

"email": "mhs@univ.ac.id",

"avatar\_url": "\[https://image.com/avatar.png](https://image.com/avatar.png)"

}

---
# API Contract Login
**Endpoint:** /api/v1/login
**Method:** POST
**Request Body (JSON):**
{
  "email": "mhs@univ.ac.id",
  "password": "rahasia_password_123"
}
**Response Body (JSON):**
{
  "status": "success",
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...",
  "user_id": 1
}

