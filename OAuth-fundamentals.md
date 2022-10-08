# OAuth 2.0 Protocol Fundamentals

- The OAuth 2.0 is a framework that allows third-party applications to obtain limited access to an HTTP service, either on behalf of a resource owner (basically a user) by orchestrating an approval interaction between the resource owner and the HTTP service (typically a content provider, such as a social network), or by allowing the third-party application to obtain access on its own behalf.

![oauth-fundamentals](https://github.com/paulveillard/cybersecurity-oauth/blob/main/img/oauthexplained.png)


## Table of Contents
- [Brief History](#brief-history)
- [What is the OAuth 2.0 framework](#what-is-the-oauth-20-framework)
  - [The client-server authentication](#)
  - [The problem with client-server auth](#)
  - [The authorization layer](#)
- [Common use cases of OAuth 2.0](#)
- [High-level description of the OAuth 2.0 mechanism](#)
- [References](#references)


## Brief History

The story of OAuth starts in November 2006 when Ma.gnolia was about to integrate its services with Appel‘s Dashboard Widgets. At the time, this kind of integration would normally be done by asking the user for their credentials on the remote system and sending the credentials to the API. The issue was, that Ma.gnolia used Twitter’s distributed identity technology – OpenID – to facilitate login. Which they don’t use credentials for authorizing and authenticating users. So Ma.gnolia looked for a solution to allow their members with OpenIDs to authorize Dashboard Widgets to access their services. A few developers from Twitter together with a developer from Ma.gnolia concluded that there were no open standards for such API access delegation.

In April 2007, this small group of developers created the OAuth discussion group, to write the draft proposal for an open protocol. In July 2007, the team drafted an initial specification. Eran Hammer joined the team and coordinated the OAuth contributions creating a more formal specification. At the beginning of December 2007, the OAuth core 1.0 final draft was released. Since then, it became a widely used open standard for access delegation.


## What is the OAuth 2.0 framework

As the brief history emphasise, the OAuth was created to address several issues and limitations pointed out with the authorization standards.

![Oauth-fundamentals-2](https://github.com/paulveillard/cybersecurity-oauth/blob/main/img/oauth-fundamentals-2.png)

- OAuth 2.0 is the industry-standard protocol for authorization. The OAuth 2.0 authorization framework enables a third-party application to obtain limited access to an HTTP service, either on behalf of a resource owner by orchestrating an approval interaction between the resource owner and the HTTP service, or by allowing the third-party application to obtain access on its own behalf.



OAuth 2.0 is an industry standard for delegated authorization, and there are a number of [OAuth providers](https://en.wikipedia.org/wiki/List_of_OAuth_providers) on the market.

![Oauth-fundamentals-3](https://github.com/paulveillard/cybersecurity-oauth/blob/main/img/oauth-fundamentals-3.jpg)

### The client-server authentication

To understand these issues, let’s visit the traditional client-server authentication model by an example:

> A bank developed a new online-banking website. The website designer thought that the UX can be improved by adding profile images. The developers said they don’t need to store the user image on their side. Instead, they can use users’ Facebook profile images. The access of the bank website to the Facebook profile image would work as follows:

The online-banking requests access restricted to the Facebook server by authenticating with the server using the user’s credentials.

![client-server](https://github.com/paulveillard/cybersecurity-oauth/blob/main/img/client-server-auth.jpg)

### The problems with client-server auth

Having the online-banking example in mind, to allow users to use their profile image, they would have to share their Facebook credentials with the bank. That means the bank will have to store the users’ Facebook credentials, typically, as clear text.

Despite the security weaknesses inherent in passwords, Facebook’s photos server is also required to support password authentication.

The bank website gains overly broad access to their users’ Facebook accounts, leaving the users without any ability to restrict duration or access scope to a limited subset of resources.

Once a user integrated their Facebook profile image, they cannot revoke bank access to their Facebook account without revoking access to all other third parties. And the only way to do so is by changing their password.
## Common use cases of OAuth 2.0
## High-level description of the OAuth 2.0 mechanism
## References


## References

The following content is based on several resources, among them are the official IETF documentation, the Wikipedia article, and OAuth 2 in Action, a book by Justin Richer and Antonio Sanso.
- [Everybody is Dancing in the OAuth 2.0 Protocol](#https://kessler.tech/security/oauth2-1/)



