# ARACLX:ENV

General introduction to our technology stack (from top-level). In future in this documentation you'll be able to find detailed information about our technical stack such as libraries, languages and tools that we're using to build products but now you need to satisfy yourself with these informations.

### Front/End

Our front-end is based mostly on `react`-like libraries. We're [**React.js**]() combined with [**MobX**]() and [`styled-components`]() to bring our PWA/SPAs to live, in case of websites we're using [**Next.js**]().

We're also using hybrid technologies to build mobile applications, we're really in love with products and libraries created by [**Ionic**]()

### Back/End

We're building back-end basing mainly on two programming languages... [**TypeScript**]() and [**Go**](), both of them providing nice performance and cool developer tooling which is fun to work with.

### DevOps

For building CI/CD We're using mostly [**Actions from GitHub**]() and [**CircleCI**](), in some kind [**Jenkins**]() aren't good solution for our software.

Contenerisation in our projects is based on [**Docker**]() and orchestration with [**Kubernetes**]() or [**Nomand**](). Sometimes we're using [**Vargant**]() to build virtual-machines which are mostly back-end on [**Ubuntu**]().

### Databases

We're using just few databases that are covering all of our needs, basically for most of our applications we're using [**MongoDB**]() and [**CockroachDB**](), combined with [**Redis**]() cache. In some specific cases we're using [**PostgreSQL**]() but that's not database which we want to use everywhere.

### Infrastucture

Our infrastructure is mostly based on **DigitalOcean**, **Scaleway**, **UpCloud** and **Google Cloud Platform**, because in our opinion these solutions are actually best IaaSes on the market. Behind IaaS we're using also some PaaS solutions - mainly **Heroku/Flynn** and **Vercel**. In case of both IaaSes that we're using we're implementing **Kubernetes** into automated infrastructure by **Terraform**.

### Design

We really love **Framer** for building UI/UX of our applications especially mobile. Behind that we're mostly using **Sketch** because it's integrations with other services that can be really helpful.

Our design solutions are **Abstract**, **InVision** and **Maze**.

Sometimes we're using **Witeboard** for discussing some design solutions, and **Octopus** for building site maps.

> You can read more about technology used by DesignOps at our company in ["Araclx DesignOps Ecosystem" document](./pages/design-ecosystem.md).

### Business Tools
We're officially moved out from [Jira]() to [Linear]() since that's solution more suitable for startups and smaller teams, where Jira is mostly focused on enterprises. Maybe in future we'll comeback to Jira but solid GitHub integration is crucial.

#### Analytics

We're not fans of collecting data from our customers, mostly we're collecting general analytical data that help us to measure grow of our products. We're using **Heap**, **Mode**/**Metabase**. In case of analytics of websites we're using [**Fathom**]().

Our software is free at fact but probably in far future every of our software will be distributed on paid models too, for analytics of things related to selling we're planning to use **Chartmogul**/**Baremetrics**.

#### Communication

> There is no actual alternative to **Slack**, but if somebody really hate slack we're recommending to take a closer look for [**Quill**]() and potentially [**RocketChat**]().

Our communication needs are covered by [**Slack**](), combined with [**Twist**](https://twist.com/) and **Tandem** at some cases. Additionally we're using [**Carrot**](https://carrot.io/)/[**Threads**](https://threads.com/) for building cross-platform posts that are important for our teams. In case of conferences or online meetings we're getting rid of Zoom and we're using [**Whereby**](https://whereby.com/).

Sometimes we're supposed supposed to collaborate on our inbox in that case we're using [**Front**]() and we really liked [**TwoBird**]() as a personal mailbox software.

#### Knowledge Management

We're organizing our knowledge by using [**Slite**](), which provides basic context for whole team about processes in our organisation and specification about our products.

> We're planning to migrate to [**Slab**]() and make it our main knowledge repository since **Slab** is much more featured than Slite.

# }
