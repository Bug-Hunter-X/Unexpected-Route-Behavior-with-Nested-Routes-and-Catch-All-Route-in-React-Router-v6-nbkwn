# React Router v6 Unexpected Route Behavior

This repository demonstrates an uncommon bug encountered when using nested routes and a catch-all route (`/contact/*`) in React Router v6. The catch-all route interferes with navigation to other routes, causing unexpected behavior.

## Bug Description

The issue arises when navigating from `/about` to `/` or another route.  Navigation will fail or result in unexpected display behavior. 

## Solution

The solution involves carefully considering the order and placement of routes within the `Routes` component and ensuring that more specific routes are defined before catch-all routes.  Sometimes restructuring the application's routes can also solve the issue.
