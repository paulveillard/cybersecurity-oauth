# OAuth 2.0

An ongoing & curated collection of awesome software best practices and techniques, libraries and frameworks, E-books and videos, websites, blog posts, links to github Repositories, technical guidelines and important resources about OAuth 2.0 and OpenID Connect in Cybersecurity.
> Thanks to all contributors, you're awesome and wouldn't be possible without you! Our goal is to build a categorized community-driven collection of very well-known resources.

## Introduction
- As an application developer, you may have heard the term OAuth 2.0 thrown around a lot. OAuth 2.0 has gained wide adoption by web service and software companies around the world, and is integral to the way these companies interact
and share information. 

![concepts](https://github.com/paulveillard/cybersecurity-oauth/blob/main/img/oauth-concepts.jpeg)

![Intro](https://github.com/paulveillard/cybersecurity-oauth/blob/main/img/oauth-flow-3.jpg)

#### But what exactly is it? In a nutshell…
> OAuth 2.0 is a protocol that allows distinct parties to share information and resources in a secure and reliable manner.

![Intro](https://github.com/paulveillard/cybersecurity-oauth/blob/main/img/oauth-flow-3.jpg)

- Developers and architects simply can’t build modern applications without running into issues of authorization and authentication.

[OAuth 2.0](https://www.couchbase.com/blog/oauth-2-oidc-fundamentals-authentication-authorization/) is an industry standard for “delegated authorization” which is the ability to provide an application or client access to data or features offered by another app or service. OAuth 2.0 focuses on authorization and is not prescriptive about authentication. OpenID Connect (OIDC) adds a standards-based authentication layer on top of OAuth 2.0.


## Tables of Contents
- [Introduction](#introduction)
- [Cloud Solutions](#cloud-solutions)
   - [Amazon Web Services (AWS)](#amazon-web-services-aws)
   - [Googe Cloud Platform (GCP)](#google-cloud-platform-gcp)
   - [Microsoft Azure](#microsoft-azure)
 
- [Authentication](#authentication)
	- [SSO#](#sso)
	- [SAML](#saml)
	- [Node.js](#authN-node)
	- [Python](#authN-python)
	- [Ruby](#authN-ruby)

- [Authorization](#authorization)
	- [OAuth](#oauth)
	

## Cloud solutions

### Amazon Web Services (AWS)
* [AWS IAM](https://aws.amazon.com/iam/) - Identity and Access Management for AWS
* [AWS SSO](https://aws.amazon.com/single-sign-on/) - Centrally manage single sign-on (SSO) access to multiple AWS accounts
* [Amazon Cognito](https://aws.amazon.com/cognito/) - SSO for business applications
* [AWS Directory Service](https://aws.amazon.com/directoryservice/) - AD in the AWS Cloud
* [AWS STS](https://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html) - AWS Security Token Service for temporary IAM tokens

### Google Cloud Platform (GCP)
* [Identity and authentication, the Google Cloud way](https://cloud.google.com/blog/products/identity-security/identity-and-authentication-the-google-cloud-way) - Overview of Google approach to identity and access management

### Microsoft Azure
* [Microsoft identity platform](https://docs.microsoft.com/en-us/azure/active-directory/develop/) - Evolution of the Azure Active Directory

## Authentication

### SSO
* [Single sign-on](https://en.wikipedia.org/wiki/Single_sign-on) - wiki page about SSO
* [Central Authentication Service (CAS)](https://github.com/apereo/cas) - Open Source Enterprise Single Sign On
* [Okta](https://www.okta.com/) - Identity and Access Management as a service; provides broad integrations
* [Auth0](https://auth0.com/) - Identity and Access Management as a service
* [Cloud-IAM](https://www.cloud-iam.com) - Keycloak IAM as a Service
* [LoginRadius](https://www.loginradius.com/) - Identity and Access Management as a service
* [FusionAuth](https://fusionauth.io/) - Identity and Access Management, either a service or self-hosted
* [PAC4J](http://www.pac4j.org/) - The security library for Java
* [buzzfeed/sso](https://github.com/buzzfeed/sso) - A single sign-on solution for securing internal services (Go based)
* [cidaas](https://www.cidaas.com) - Cloud Identity & Access Management (Identity and Access Management as a service)

### SAML
* [SAML](https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language) - Security Assertion Markup Language wiki page
* [Spring Security SAML](http://projects.spring.io/spring-security-saml/) - SAML implementation for Spring
* [SAMLTest](https://samltest.id/) SAML Testing service
* [SAMLkit](https://samlkit.com/) Development/testing entity

### Two-factor authentication
* [U2F and UAF spec](https://fidoalliance.org/specifications/overview/) - 2FA specifications
* [Two Factor Auth](https://twofactorauth.org/) - List of websites with 2FA info

## Passwordless authentication
* [MojoAuth](https://mojoauth.com/) - Email and WebAuthN Authentication
* [Sawolabs](https://sawolabs.com/) - Authentication without OTPs and Passwords

## Authorization

### OAuth
#### Site
* [OAuth on Wikipedia](https://en.wikipedia.org/wiki/OAuth)
* [OAuth.net by Okta](https://oauth.net/)
* [OAuth.com by Okta](https://www.oauth.com/)
* [OAuth Articles and Posts by Alex Bilbie](https://alexbilbie.com/tag/oauth/)
* [OpenID Connect](https://openid.net/connect/)

#### Specification

##### Formal
* [The OAuth 2.0 Authorization Framework (RFC 6749)](https://tools.ietf.org/html/rfc6749)
* [The OAuth 2.0 Authorization Framework: Bearer Token Usage (RFC 6750)](https://tools.ietf.org/html/rfc6750)
* [OAuth 2.0 Threat Model and Security Considerations (RFC 6819)](https://tools.ietf.org/html/rfc6819)
* [OAuth 2.0 Token Revocation (RFC 7009)](https://tools.ietf.org/html/rfc7009)
* [JSON Web Signature (JWS) (RFC 7515)](https://tools.ietf.org/html/rfc7515)
* [JSON Web Encryption (JWE) (RFC 7516)](https://tools.ietf.org/html/rfc7516)
* [JSON Web Key (JWK) (RFC 7517)](https://tools.ietf.org/html/rfc7517)
* [JSON Web Algorithms (JWA) (RFC 7518)](https://tools.ietf.org/html/rfc7518)
* [JSON Web Token (JWT) (RFC 7519)](https://tools.ietf.org/html/rfc7519)
* [Examples of Protecting Content Using JSON Object Signing and Encryption (JOSE) (RFC 7520)](https://tools.ietf.org/html/rfc7520)
* [Assertion Framework for OAuth 2.0 Client Authentication and Authorization Grants (RFC 7521)](https://tools.ietf.org/html/rfc7521)
* [SAML 2.0 Profile for OAuth 2.0 Client Authentication and Authorization Grants (RFC 7522)](https://tools.ietf.org/html/rfc7522)
* [JSON Web Token (JWT) Profile for OAuth 2.0 Client Authentication and Authorization Grants (RFC 7523)](https://tools.ietf.org/html/rfc7523)
* [OAuth 2.0 Dynamic Client Registration Protocol (RFC 7591)](https://tools.ietf.org/html/rfc7591)
* [OAuth 2.0 Dynamic Client Registration Management Protocol (RFC 7592)](https://tools.ietf.org/html/rfc7592)
* [Proof Key for Code Exchange by OAuth Public Clients (RFC 7636)](https://tools.ietf.org/html/rfc7636)
* [OAuth 2.0 Token Introspection (RFC 7662)](https://tools.ietf.org/html/rfc7662)
* [JSON Web Signature (JWS) Unencoded Payload Option (RFC 7797)](https://tools.ietf.org/html/rfc7797)
* [Authentication Method Reference Values (RFC 8176)](https://tools.ietf.org/html/rfc8176)
* [OAuth 2.0 for Native Apps (RFC 8252)](https://tools.ietf.org/html/rfc8252)
* [OAuth 2.0 Authorization Server Metadata (RFC 8414)](https://tools.ietf.org/html/rfc8414)
* [OAuth 2.0 Device Authorization Grant (RFC 8628)](https://tools.ietf.org/html/rfc8628)
* [OAuth 2.0 Mutual TLS Client Authentication and Certificate-Bound Access Tokens (RFC 8705)](https://tools.ietf.org/html/rfc8705)
* [OAuth 2.0 Token Exchange (RFC 8693)](https://tools.ietf.org/html/rfc8693)
* [JSON Web Token Best Current Practices (RFC 8725)](https://tools.ietf.org/html/rfc8725)
* [The OAuth 2.0 Authorization Framework: JWT-Secured Authorization Request(JAR) (RFC 9101)](https://datatracker.ietf.org/doc/html/rfc9101)

##### Draft
* [OAuth 2.0 Incremental Authorization(draft-ietf-oauth-incremental-authz-04)](https://tools.ietf.org/html/draft-ietf-oauth-incremental-authz-04)
* [OAuth 2.0 Token Binding (draft-ietf-oauth-token-binding-08)](https://tools.ietf.org/html/draft-ietf-oauth-token-binding-08)
* [OAuth 2.0 Security Best Current Practice (draft-ietf-oauth-security-topics-18)](https://tools.ietf.org/html/draft-ietf-oauth-security-topics-18)
* [Reciprocal OAuth (draft-ietf-oauth-reciprocal-04)](https://tools.ietf.org/html/draft-ietf-oauth-reciprocal-04)
* [OAuth 2.0 for Browser-Based Apps(draft-ietf-oauth-browser-based-apps-08)](https://tools.ietf.org/html/draft-ietf-oauth-browser-based-apps-08)
* [The OAuth 2.1 Authorization Framework(draft-ietf-oauth-v2-1-04)](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-v2-1-04)

### Article
* OAuth 2.0 系列文 by [Yucheng Chuang](https://twitter.com/yorkxin)
    * [(1) 世界觀](http://blog.yorkxin.org/posts/2013/09/30/oauth2-1-introduction/)
    * [(2) Client 的註冊與認證](http://blog.yorkxin.org/posts/2013/09/30/oauth2-2-cilent-registration/)
    * [(3) Endpoints 的規格](http://blog.yorkxin.org/posts/2013/09/30/oauth2-3-endpoints/)
    * [(4.1) Authorization Code Grant Flow 細節](https://blog.yorkxin.org/2013/09/30/oauth2-4-1-auth-code-grant-flow)
    * [(4.2) Implicit Grant Flow 細節](https://blog.yorkxin.org/2013/09/30/oauth2-4-2-implicit-grant-flow)
    * [(4.3) Resource Owner Credentials Grant Flow 細節](https://blog.yorkxin.org/2013/09/30/oauth2-4-3-resource-owner-credentials-grant-flow)
    * [(4.4) Client Credentials Grant Flow 細節](https://blog.yorkxin.org/2013/09/30/oauth2-4-4-client-credentials-grant-flow)
    * [(5) 核發與換發 Access Token](https://blog.yorkxin.org/2013/09/30/oauth2-5-issuing-tokens)
    * [(6) Bearer Token 的使用方法](https://blog.yorkxin.org/2013/09/30/oauth2-6-bearer-token)
    * [(7) 安全性問題](https://blog.yorkxin.org/2013/09/30/oauth2-7-security-considerations)
    * [各大網站 OAuth 2.0 實作差異](https://blog.yorkxin.org/2013/09/30/oauth2-implementation-differences-among-famous-sites)
* [OAuth 2 Simplified by Aaron Parecki](https://aaronparecki.com/oauth-2-simplified/)
* [理解OAuth 2.0 by 阮一峰](http://www.ruanyifeng.com/blog/2014/05/oauth_2_0.html)
* [帮你深入理解OAuth2.0协议](http://blog.csdn.net/seccloud/article/details/8192707)

### Book
* [OAuth 2 in Action](https://www.manning.com/books/oauth-2-in-action)
* [Getting Started with OAuth 2.0 - Programming Clients for Secure Web API Authorization and Authentication](http://shop.oreilly.com/product/0636920021810.do)
* [Identity and Data Security for Web Development - Best Practices](http://shop.oreilly.com/product/0636920044376.do)
* [OAuth 2.0 – Getting Started in Web-API Security](https://api-university.com/books/oauth-2-0-book/)

### Playground
* [OAUTH.TOOLS](https://oauth.tools/)
* [Google OAuth 2.0 Playground](https://developers.google.com/oauthplayground/)
* [RFC6749](https://tools.ietf.org/html/rfc6749) - RFC with OAuth2 definition
* [Spring Security OAuth](http://projects.spring.io/spring-security-oauth/) - OAuth implementation for Spring
* [OAuth server for PHP](http://bshaffer.github.io/oauth2-server-php-docs/) - OAuth server for PHP
* [ORY Hydra](https://www.ory.sh/hydra/) - Go based OAuth and OIDC server
* [JSON Web Tokens](http://jwt.io/) - All you need to know about JWT
* [OAuth+JWT in microservices](https://www.youtube.com/watch?v=BdKmZ7mPNns) - Good video on how to use tokens in microservices
* [OpenID Connect](http://openid.net/connect/) - Identity layer on top of OAuth
* [oauth2-proxy](https://github.com/oauth2-proxy/oauth2-proxy) - A reverse proxy that provides authentication with Google, Github or other providers.


* [Role-based access control](https://en.wikipedia.org/wiki/Role-based_access_control) - wiki page about RBAC
* [XACML](https://en.wikipedia.org/wiki/XACML) - XML-based access control markup language
* [angular-permissions](https://github.com/Narzerus/angular-permission) authorization for AngularJS

## Access management
* [Keycloak](https://www.keycloak.org/) - Open Source Identity and Access Management
* [IdentityServer](https://identityserver.io/) - .NET based IAM server
* [ORY](https://www.ory.sh/) - Open Source Identity Infrastructure and Services (Go based)
* [casbin](https://casbin.org/en/) - Go authorization library
* [OpenAM](https://forgerock.github.io/openam-community-edition/) - (discontinued), successor of OpenSSO
* [WSO2 Identity Server](http://wso2.com/products/identity-server/) - also has SSO, authZ, ...

## Tools
* [Step CLI](https://smallstep.com/cli/) - A zero trust swiss army knife for working with X509, OAuth, JWT, OATH OTP, etc. 
* [JWT DEBUGGER](https://jwt.ssotools.com/)  - A simple JWT decoder tool, that can help to verify the JWT and with the help of signature.

## Other aggregators
* [awesome-keycloak](https://github.com/thomasdarimont/awesome-keycloak) - A curated list of Keycloak related resources
* [casbin/awesome-auth](https://github.com/casbin/awesome-auth) - other auth list
* [OAuth code libraries](https://oauth.net/code/)
* [OIDC code libraries](https://openid.net/developers/libraries/)
