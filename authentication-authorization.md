
## Authentication versus authorization
Before we dive into our discussion of OAuth 2.0, it is important to first define some terms. There are two terms in particular that are pivotal to our understanding of


> OAuth 2.0 and its uses: authentication and authorization. These terms are often conflated and sometimes interchanged, but they actually represent two distinct
concepts, and their distinction is important to understand before continuing our discussion of OAuth 2.0.


### Authentication
- Authentication is the process of validating whether a person (or system) is
actually who they say they are.

> An example of this is when you go to the bank to withdraw money, and you
provide your bank card and PIN to the teller. In some cases, the teller may ask
for additional identification, such as your driver's license, to verify your identity.
You may recognize this in other instances when you provide your username and
password to a website, say, to view a document.


### Authorization

- Authorization is the process of determining what actions you are allowed to
perform once you have been authenticated.


> Referring to our previous bank example, once the teller has verified who you are,
they can then proceed to fulfill your request to withdraw money. In order to do this,
they must check whether you are allowed to withdraw money from the account that
you are requesting (that is, you are actually the owner of the account). Relating to
our website example, once you have authenticated by providing your username
and password, the website will then check to see whether you are indeed allowed
to see the document that you are requesting. This is usually done by looking up
your permissions in some access control list.
Now that we have established the distinction between these two important
concepts, we can look at what OAuth 2.0 actually is and the problems it solves.
