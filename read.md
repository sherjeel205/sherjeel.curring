Stateless Behavior of Daraz App:
Daraz app uses stateless architecture, meaning the server doesn't store user session data between requests. Instead, each request (like browsing products or adding items to the cart) carries all the necessary information (like tokens) to identify the user. This ensures scalability and faster response times, as the server treats each request independently without remembering past interactions.
Authentication:
Daraz uses authentication to verify users' identities, typically via login credentials (email/phone and password). After successful login, the user gets a token which proves their identity.
Authorization:
Authorization happens after authentication. It determines what resources a user can access for example regular users can browse products, while sellers can list items.Authorization ensures that users can only perform actions they have permission for.






