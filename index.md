---

layout: col-sidebar
title: OWASP Application Gateway
tags: iam, oauth2
level: 1
type: tool
pitch: OWASP Application Gateway is an HTTP proxy that handles Oauth2 authentication and session management

---

[![OWASP Incubator](https://img.shields.io/badge/owasp-incubator-blue.svg)](https://owasp.org/www-project-application-gateway/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/gianlucafrei/Application-Gateway/blob/main/LICENSE)
[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/gianlucafrei/nellygateway)](https://github.com/gianlucafrei/Application-Gateway/releases)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/5eaa206a103e4b28be9da2ba857d1653)](https://app.codacy.com/gh/gianlucafrei/nellygateway?utm_source=github.com&utm_medium=referral&utm_content=gianlucafrei/nellygateway&utm_campaign=Badge_Grade)
[![Java CI with Maven](https://github.com/gianlucafrei/nellygateway/workflows/Java%20CI%20with%20Maven/badge.svg)](https://github.com/gianlucafrei/Application-Gateway/actions?query=workflow%3ACI%2FCD)

🏗️ **OWASP Application Gateway is work-in-progress. No productive version has been released yet.**

## What is the OWASP Application Gateway?

OWASP Application Gateway is an HTTP reverse proxy that sits between your web application and the client and handles Oauth2 login and session management. For you, as a developer, OWASP Application Gateway removes the hassle to implement complicated oauth2 logic in the backend and frontend so you can focus totally on your applications logic.

## Abstract

<script async class="speakerdeck-embed" data-id="03a8b5ec38aa4979aab3f106d06a3aa5" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>

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
- CSRF protection
- Rolling sessions
- W3C compliant request tracing  

See also the documentation [GitHub](https://github.com/gianlucafrei/Application-Gateway)

## Contributing

All kinds of contributions are much wanted and highly appreciated! You can help us with coding, writing documentation, propose architectural improvements, test the prototype, advocate the project or any other kind of activity. Please make sure to read the [CONTRIBUTION.md](https://github.com/gianlucafrei/Application-Gateway/blob/main/CONTRIBUTING.md) before you start coding. If you have any questions or are not sure how exactly you can contribute feal free to contact any of the project leaders.
