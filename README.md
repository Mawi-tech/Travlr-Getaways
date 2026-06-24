# CS465-Fullstack: Full Stack Development

## Overview
This repository captures the early build of Travlr Getaways, a full-stack travel booking site developed across the CS-465 course modules. At this stage, the project is an Express server rendering server-side views, laying the foundation for the MEAN-stack (MongoDB, Express, Angular, Node.js) application it grows into in later modules.

## Approach
I structured the backend using the Express MVC pattern, organizing controllers, routes, and views into an app_server directory to keep request handling, business logic, and presentation cleanly separated. Static assets like CSS and images are served alongside server-rendered Handlebars views, giving the site a working front end before any client-side framework or database layer is introduced.

## Reflection
Starting with a server-rendered baseline before adding Angular and MongoDB reinforced how much a clean separation of concerns up front simplifies later integration work. Building out the controllers, routes, and views as distinct, well-organized pieces made it straightforward to extend the application module by module without having to restructure existing code.

## Skills Demonstrated
- Express.js MVC architecture
Server-side rendering with Handlebars
RESTful route organization
Incremental, module-based development
