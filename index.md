---

layout: col-sidebar
title: OWASP Application Gateway
tags: iam, oauth2, oag
level: 2
type: tool
pitch: OWASP Application Gateway is an HTTP proxy that handles Oauth2 authentication and session management and can issue verifyable JWT tokens for downstream systems.

---

[![OWASP Incubator](https://img.shields.io/badge/owasp-incubator-blue.svg)](https://owasp.org/www-project-application-gateway/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/gianlucafrei/Application-Gateway/blob/main/LICENSE)
[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/gianlucafrei/nellygateway)](https://github.com/gianlucafrei/Application-Gateway/releases)
[[Java CI with Maven](https://github.com/OWASP/www-project-application-gateway/blob/main/assets/images/Shield.png?raw=true)](https://github.com/gianlucafrei/Application-Gateway/actions?query=workflow%3ACI%2FCD)

🏗️ **OWASP Application Gateway is work-in-progress. No productive version has been released yet. - We are on Version 0.5.1.**

<a href="https://github.com/gianlucafrei/Application-Gateway/wiki"><img src="https://raw.githubusercontent.com/gianlucafrei/Application-Gateway/main/doc/pictures/Banner.png" width="500" /></a>
## What is the OWASP Application Gateway?

OWASP Application Gateway is an HTTP reverse proxy that sits between your web application and the client and handles Oauth2 login, session management as well as other security aspects and operational requirements (including for example correlation logging / tracing). For you, as a developer, OWASP Application Gateway removes the hassle to implement complicated oauth2 logic in the backend and frontend so you can focus totally on your applications logic. OAG is built in an extendable way, so that it is easy to customize it with your own code when required.

<a href="https://github.com/gianlucafrei/Application-Gateway"><img src="https://github.com/gianlucafrei/Application-Gateway/blob/main/doc/OAG-Overrview.png?raw=true" alt="Overview diagram of OAG"></a>

## Abstract

See: <a href="https://speakerdeck.com/gianlucafrei/owasp-application-gateway-abstract">Speakerdeck</a>

## Functionality

- HTTPS Redirection with Proxy Awareness
- OpenID Connect Login with multiple providers
- Multiple Backend routes
- Authenticated routes
- Request Logging
- Add and remove response headers
- Secure, HTTP-only and same-site session cookies
- Forward id token to backend
- Upstream authentication with API key
- GitHub Login support
- Method whitelisting
- CSRF Protection
- Correlation logging / Tracing
- more to come...

See also the documentation [GitHub](https://github.com/gianlucafrei/Application-Gateway/wiki)

## Contributing

All kinds of contributions are much wanted and highly appreciated! You can help us with coding, writing documentation, propose architectural improvements, test the prototype, advocate the project or any other kind of activity. Please make sure to read the [CONTRIBUTION.md](https://github.com/gianlucafrei/Application-Gateway/blob/main/CONTRIBUTING.md) before you start coding. If you have any questions or are not sure how exactly you can contribute feal free to contact any of the project leaders.
