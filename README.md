This monorepo was created with Turborepo, the projects are located in `/apps` folder.

1. Enter `api` folder `cd apps/api`
2. Run `npm run migrations:create test`

If I run `npx node-pg-migrate create test` in root it works but the project that needs this migrations are located inside `/apps` folder, and the migration command should be executed inside `/apps/api` folder.
