---
'@scalar/api-client': minor
'@scalar/express-api-reference': patch
'@scalar/fastify-api-reference': patch
'@scalar/hono-api-reference': patch
'@scalar/swagger-editor': patch
'@scalar/api-reference': patch
'@scalar/use-toasts': patch
'@scalar/use-modal': patch
'@scalar/themes': patch
---

- Removed activeBreadCrumb from api-client as its available in the slot
- Centralized navigation logic
- use proper anchor navigation instead of scrollIntoView, it will also be saved to history
- scrolling down will open the next section
