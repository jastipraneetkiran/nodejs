# Chapter Overview
> Professionally speaking, the ability to rapidly create web services with mock data that can run locally is a useful skill. Sometimes we might have limited access or even no access to services we are integrating with. This might be because they have not yet been created or because of slow-performance, or down-time or permission issues.

> Sometimes staging environments that we would integrate into our local development environment are shared among teams. This can lead to unexpected results, because another developer may trigger a state change in the shared staging environment. Ideally, we can run instances of production services with their own local state on our machine and integrate with those. However, organizations may not yet have this capability. Another reason for mocking web services is for rapid prototyping. This is especially convenient in situations where client-side development has the advantage of being able to specify the data model. For these situations, we can mock our web services.

>In this chapter we will explore how to create mock services quickly and efficiently with Node.js.

## Learning Objective
By the end of this chapter, you should be able to:

- Create a local file server with minimal effort.
- Create a very basic mock service with just Node.js core.
- Discuss how to rapidly scaffold a Fastify service for more involved mock services.