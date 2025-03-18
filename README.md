# Tanstack Query Example (aka React Query)

This project is a demonstration of how to use [Tanstack Query](https://tanstack.com/query/latest/docs/react/overview) and [Axios](https://github.com/axios/axios) to perform the following tasks:

- CRUD Operations (`useQuery`, `useMutation`).
- Pagination (`useQuery`)
- Load-more like feature (`useInfiniteQuery`)

## Run Locally

- Clone the project

```bash
git clone https://github.com/dipankarbarman714/react-query
```

- Go to the project directory:

```bash
cd react-query
# or cd react-query-example-main
```

- Install dependencies

```bash
npm install
```

- Setup database file

```bash
cp db/sample.db.json db/db.json
```

- Start the `json-server`

```bash
npm json-server
```

- Launch another terminal and start the `Vite` server

```bash
npm dev
```

Head over to your browser and open the URL <http://localhost:5555> to access the application. You can change the port in `vite.config.ts`

