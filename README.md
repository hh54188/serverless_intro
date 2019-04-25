# Serverless Introduction

- Old Way

  - VPS (Linode & Digital Ocean)
  - PaaS (Heroku)
  - SaaS
  - Backdraws

- No Server

  - Github Pages
  - Netlify

- Martin Fowler: <https://martinfowler.com/articles/serverless.html>

  - BaaS: Serverless was first used to describe applications that significantly or fully incorporate third-party, cloud-hosted applications and services (Auth0)

  - FaaS: Serverless can also mean applications where server-side logic is still written by the application developer, but, unlike traditional architectures, it’s run in stateless compute containers that are event-triggered, ephemeral (may only last for one invocation), and fully managed by a third party. (Firebase, AWS Lambda)

  - FaaS VS PaaS VS Container:  

    - ### Reduced operational cost 

    - ### BaaS: reduced development cost

    - ### **scaling is automatically managed, transparent, and fine grained**

    - **No Ops**: “Ops” means a lot more than server administration. It also means—at least—monitoring, deployment, security, networking, support, and often some amount of production debugging and system scaling.

  - Example :

    - #### occasional requests

    - #### inconsistent traffic