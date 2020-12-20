# ds-workbench
A local development data science workbench for integrating production-like workflows

## About

This is a data scientist workbench for locally tracking data and model artifacts in a production-like way. This code is only intended to give you better tools for local workflow management, and this should not be used in production. To read more about my motivation, read [my blog post](https://emilygorcenski.com/post/configuring-a-data-science-workbench/) about it.

## Setup

You will need Docker installed.

Clone the repo. Edit `default.env`, or create a new `env` file, with your own preferred secrets.

Run the services using `docker-compose --env-file default.env up -d`, substituting if necessary your custom environment file.

This is not warranted nor actively maintained. Please feel free to adjust this to your own use cases.
