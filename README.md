[![Quarto Publish](https://github.com/vanHeemstraSystems/content-management/actions/workflows/publish.yml/badge.svg)](https://github.com/vanHeemstraSystems/content-management/actions/workflows/publish.yml)

content-management
# Content Management

Can be read as "Content Management" at https://app.gitbook.com/s/Rs3XPuVclvoj92Exb9AA/

Can be browsed as "Content Management" at https://vanheemstrasystems.github.io/content-management/

Documentation of this repository is automatically done with Quarto using GitHub Actions as described at https://github.com/vanHeemstraSystems/quarto-to-github-pages/blob/main/300/300/README.md

Based on "How to Run PostgreSQL and pgAdmin Using Docker" at https://towardsdatascience.com/how-to-run-postgresql-and-pgadmin-using-docker-3a6a8ae918b5

Based on "JointJS - React Example App With TypeScript And SCSS Using Create-React-App" at https://resources.jointjs.com/tutorial/react-ts

Based on "Sanity" at https://sanity.io

Create yarn.lock file as follows:

```
$ cd containers/app/main
$ yarn install
```

Run as follows:

```
$ cd containers/app
$ docker-compose --file docker-compose.dev.yml --project-name content-management-dev up --build -d
```
