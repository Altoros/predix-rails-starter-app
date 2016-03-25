# Predix Rails Starter App

Sample Ruby on Rails application ready to be deployed to GE Predix.

## Prerequisites

- Ruby 2.3.0
- Node.js
- PostgreSQL
- Cloud Foundry CLI

## Installation

    git clone https://github.com/dskecse/predix-rails-starter-app
    cd predix-rails-starter-app
    bin/setup

## Deployment

    cf create-service postgres shared-nr rails-postgres
    cf push [your-app-name]
