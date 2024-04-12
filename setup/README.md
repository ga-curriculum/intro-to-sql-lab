# ![SQL Where in the World is Carmen Sandiego - Setup](./assets/hero.png)

## Setup

Open your Terminal application and navigate to your `~/code/ga/labs` directory:

```bash
cd ~/code/ga/labs
```

Fork and clone the [starter code](https://git.generalassemb.ly/modular-curriculum-all-courses/sql-where-in-the-world-is-carmen-sandiego-lab-starter-code).

Change into the directory:

```bash
cd sql-where-in-the-world-is-carmen-sandiego-lab-starter-code
```

Create a new database called world and populate it with the SQL found in `world.sql`:

```bash
psql -f world.sql
```

Start `psql` and connect to the new database called `world`:

```bash
psql -d world
```

Use the `\d` command to see what tables are available. You should see:

| Schema | Name | Type | Owner |
| -- | -- | -- | --|
|public | cities | table | your-username |
|public | countries | table | your-username |
|public | countrylanguages | table | your-username |

Now that you are connected to `psql` and see your tables, you're ready to start.