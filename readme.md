# Talk4ME

This Repo contains all the submodules used to build [Talk4Me](https://talk4me.tochibedford.com)

![App Image](./talk2me_frontend_next/public/talk4me.png)

## Frontend

Built with Next & sass

## Backend

Built with Python (FastAPI) and Uvicorn.

## Cloud functions

The cloud function makes a call to open AI directly. Had to port from vercel cloud functions to google cloud functions because of the 10 second timeout on vercel for serverless functions.
