## Components of spring security
* **Security Filter:** Every Request/Response is pass though security filter
* **Authenticcation Provider:** Different type of authentication provide to authentication user most common id Dao based authentication provider to authenticate user againt DB with Password Encoder
* **Authenticcation Manager:** Loop through the available Authenticcation Provider and ask for authentication
* **UserDetailsService:** Used by DaoAuthenticationPProvide to get User Details (Authenticated Object)
* **Security Context/ Principle:** Authenticated User Details
* **Security Context Holder:** Basically the holder of Security Context 
