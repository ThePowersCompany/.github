## The Powers Company Github

- [Powers P3 - Management Operating System](https://www.powers-p3.com/)

Our software projects are currently split across four repositories.

- Frontend / UI

  - [next](https://github.com/ThePowersCompany/next) (Next.js React Web Application)
  - [native](https://github.com/ThePowersCompany/native) (Expo React Native Mobile Application)

- Backend

  - [server](https://github.com/ThePowersCompany/server)(Zig Backend API Server)

- Microcontrollers
  - [micro](https://github.com/ThePowersCompany/micro) (ESP32 Espressif Idf C framework)

## We use Github Projects and Views for Project Management. We track issues in the board view.

- [Project - Powers Software](https://github.com/orgs/ThePowersCompany/projects/3)

You'll find a board view here for each of the repositories.

## Infrastructure

We use Vercel to host our Next.js Web Application.

- [Vercel - Powers](https://vercel.com/the-powers-company/powers)

We use Digital Ocean to host our Zig Backend API Server.

- [Digital Ocean - API Server Project](https://cloud.digitalocean.com/projects/0ad80166-e52f-4bb9-831e-6f84f9c48a19/resources?i=a249da)

We have two servers on Digital Ocean for Staging and Production instances of our Backend.

- Staging - 64.225.0.10:3333 or https://staging.powers-p3.com:3333
- Production - 161.35.179.38:3333 https://prod.powers-p3.com:3333

We use Supabase for our managed PostgreSQL database.

- [Supabase Powers Organization](https://supabase.com/dashboard/projects)

We have two database instances for Staging and Production.

- [Staging DB](https://supabase.com/dashboard/project/vjdpcabrnelrhyzdwqpd)

```bash
# IPV4 - no pooler
DATABASE_URL="postgresql://postgres:horsewater10gallon@db.vjdpcabrnelrhyzdwqpd.supabase.co:5432/postgres?connection_limit=5"
```

- [Production DB](https://supabase.com/dashboard/project/jnqaulbqopvillqcrqbd)

```bash
# IPV4 - no pooler
DATABASE_URL="postgresql://postgres:2qxEH1J8ubCQqMfz@db.jnqaulbqopvillqcrqbd.supabase.co:5432/postgres?connection_limit=1&pool_timeout=20"
```

## CI / Testing / Deployment

We are using Github actions for CI. There is various testing and deployment scripts set up to automate the process. Please refer to each repositories README for more info on how this is implemented in the environment.
