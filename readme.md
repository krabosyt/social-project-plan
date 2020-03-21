# Social Media Project

## An experiment

### Goal of this project

- Experiment with different technologies, primarily `js`
- Build a social media platform, no bullshits in it, just a platform to connect people, talk to each other, post whatever they want for their friends, that's it.

### Features list

- [ ] Login/Registration
- [ ] Chat functionality
- [ ] Friends functionality
- [ ] Profiles
- [ ] Personal page, friends can view it
- [ ] Comments functionality
- [ ] Notification center
- **We gonna add more to this list as we go on**

### Technologies

- Setup the whole workspace using `nx`, a monorepo solution by `nwrl`
- For the backend services we going to use `express` with `typescript`
- For the user management, we can either implement a passport strategy or use `keycloak`, im not decided yet.
- Obviously we are using `typescript`, no reason not to really.
- We **might** make a graphql layer between our backend and our frontend, if we do then we going to use **apollo server**
- For the frontend we going to use **react**, the only reason is because i know this framework better than others
- For database, we going to use **typeorm** with postgress.
- For the realtime stuff (chat, notifications) we going to use **socket.io** in combination with redis, of course we gonna use redis in **persistence** mode
- We going to use **docker** to provision everything we need.
- **We gonna add more to this list as we go on**

### Roadmap

- [ ] Setup the `nx workspace`
- [ ] Setup an initial `docker compose` file to provision a database, maybe the redis as well
- [ ] Setup an initial `express` service and make a connection to our database using typeorm.
- [ ] Setup our frontend `react` application.
- [ ] Connect our frontend with our backend using a simple endpoint.
- [ ] Setup our keycloak server, create a realm for development, create an initial client for our frontend, setup our roles, create a client for our express service.
- [ ] Create a connection to the frontend client we created previously with keycloak and protect an endpoint to the backend.
- ...more to come.
