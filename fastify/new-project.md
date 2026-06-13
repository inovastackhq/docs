### Install Fastify CLI

```sh
npm install --global fastify-cli
```

### Create a new TypeScript project

```sh
fastify generate my-project-name --lang=ts
```

### Move into the project and install dependencies

```sh
cd my-project-name
npm install
```

### Install common packages

Install only what your project needs.

```sh
npm i dotenv @fastify/cors axios jsonwebtoken camaro
npm i @aws-sdk/client-dynamodb @aws-sdk/util-dynamodb @aws-sdk/client-secrets-manager
npm i --save-dev @types/jsonwebtoken @types/node
```

### Optional: OpenAPI and security packages

```sh
npm i @fastify/swagger @fastify/swagger-ui @fastify/helmet @fastify/rate-limit
```

### Optional: Redis and scheduling packages

```sh
npm i @fastify/redis @fastify/schedule toad-scheduler
```
