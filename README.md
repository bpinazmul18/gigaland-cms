# Strapi application

A quick description of your strapi application

## Dependency security

The project is currently maintained on Strapi 3. Strapi and its bookshelf
connector require Knex `0.21.18`, so upgrading Knex to the patched 2.x
release is not compatible with this stack. The Strapi and Knex Dependabot
alerts require a separate migration to Strapi 4; do not override the
connector's Knex peer dependency as a shortcut.
