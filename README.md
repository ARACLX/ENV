# ARACLX:ENV

General introduction to our technology stack (from top-level). In future in this documentation you'll be able to find detailed information about our technical stack such as libraries, languages and tools that we're using to build products but now you need to satisfy yourself with these informations.

### Front/End

Our front-end is based mostly on `react`-like libraries. We're [**React.js**]() combined with [**MobX**]() and [`styled-components`]() to bring our PWA/SPAs to live, in case of websites we're using [**Next.js**]().

We're also using hybrid technologies to build mobile applications, we're really in love with products and libraries created by [**Ionic**]()

### Back/End

We're building back-end basing mainly on two programming languages... [**TypeScript**]() and [**Go**](), both of them providing nice performance and cool developer tooling which is fun to work with.

<!-- ### DevOps

- GitHub Actions / CircleCI
- SonarQube
- Terraform
- Docker
- Kubernetes
- Ubuntu
- Jaeger -->

### Databases

We're using just few databases that are covering all of our needs, basically for most of our applications we're using [**MongoDB**]() and [**CockroachDB**](), combined with [**Redis**]() cache. In some specific cases we're using [**PostgreSQL**]() but that's not database which we want to use everywhere.

### Infrastucture

Our infrastructure is mostly based on **DigitalOcean** and **Google Cloud Platform**, because in our opinion these solutions are actually best IaaSes on the market. Behind IaaS we're using also some PaaS solutions - mainly **Heroku/Flynn** and **Vercel**. In case of both IaaSes that we're using we're implementing **Kubernetes** into automated infrastructure by **Terraform**.

<!-- ### Design -->

### Business Tools

> Currently we're using **Jira** and **ZenHub** for issue management, but we're found some interesting alternatives - **Zepel**, **Clubhouse** and **Linear**. They both are simple to use, yet powerful tools but since they don't have integrations yet it's hard to introduce them to our workflow.

Our communication needs are covered by **Slack**, combined with [**Twist**](https://twist.com/) and **Tandem** at some cases. Additionally we're using [**Carrot**](https://carrot.io/)/[**Threads**](https://threads.com/) for building cross-platform posts that are important for our teams. In case of conferences or online meetings we're getting rid of Zoom and we're using [**Whereby**](https://whereby.com/).

We're organizing our knowledge by using [**Slite**](), which provides basic context for whole team about processes in our organisation and specification about our products.

> We're planning to migrate to [**Slab**]() and make it our main knowledge repository since **Slab** is much more featured than Slite.

# }
