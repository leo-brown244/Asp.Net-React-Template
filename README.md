# ASP.NET Core / React SPA Template App

This app is a template application using ASP.NET Core 3.1 for a REST/JSON API server and React for a web client.

![screen recording 2017-06-10 at 04 12 pm](https://user-images.githubusercontent.com/759811/27006360-bd3b8152-4df7-11e7-9011-f22204abe4d5.gif)

## Overview of Stack
- Server
  - ASP.NET Core 3.1
  - PostgreSQL 10
  - Entity Framework Core w/ EF Migrations
  - JSON Web Token (JWT) authorization
  - Docker used for development PostgreSQL database and MailCatcher server
- Client
  - React 16
  - Webpack for asset bundling and HMR (Hot Module Replacement)
  - CSS Modules
  - Fetch API for REST requests
- Testing
  - xUnit for .NET Core
  - Enzyme for React
  - MailCatcher for development email delivery
- DevOps
  - Ansible playbook for provisioning (Nginx reverse proxy, SSL via Let's Encrypt, PostgreSQL backups to S3)
  - Ansible playbook for deployment

## Demo

[![Demo Video](https://cloud.githubusercontent.com/assets/759811/26319096/4075a7e2-3ee3-11e7-8017-26df7b278b27.png)](https://www.youtube.com/watch?v=xh5plRGg3Nc)
