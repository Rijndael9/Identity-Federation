# Identity-Federation

Prepare a complete demo for the OpenID Connect Basic and Implicit profiles including creating
clients and finding a provider in the open source community.

Idea: make an application (blog) with the ability to add comments by authorized users. Authorization occurs through social networks.

We used the Auth0 service module. Its ask the user to log in, and then save the token and profile to the local store.
After the authorization, the user can add a post under his nickname, as well as we receive from him a photo and email address.
