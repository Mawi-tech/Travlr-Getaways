# Travlr Getaways

Full-stack travel booking application built on the MEAN stack. Two front ends
share one MongoDB database: a server-rendered customer site and a single-page
admin console behind JWT authentication.

## Architecture

- `app_server/` - Express customer-facing site, server-rendered views
- `app_api/` - REST API, Mongoose models and controllers
- `app_admin/` - Angular SPA for trip administration
- `app.js` - Express entry point wiring both server and API routes

## Stack

Node.js, Express, MongoDB, Mongoose, Angular, TypeScript, JWT

## Running locally

    npm install
    # create .env with MONGODB_URI and JWT_SECRET
    npm start

## Notes

Admin routes are protected by middleware that validates a JWT before the
request reaches the controller.
