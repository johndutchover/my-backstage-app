# [Backstage](https://backstage.io)

## [Getting Started Guide](https://backstage.io/docs/getting-started/)

### App 

#### Development
- backstage-dev/

##### Packages
- app
- backend
 
###### yarn backstage-cli info
```text
OS:   Darwin 23.0.0 - darwin/arm64
node: v20.11.1
yarn: 4.1.0
cli:  0.25.2 (installed)
backstage:  1.23.3
```

##### Database

```yaml
backend:
  baseUrl: http://localhost:7007
  listen:
    port: 7007
  database:
    client: better-sqlite3
    connection: ':memory:' 
```

##### Start the app

```bash
cd backstage-dev
yarn install
yarn dev
```
