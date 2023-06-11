## Basics of sequelize orm

### Migrations

install sequelize cli

```.sh
npm install --save-dev sequelize-cli
```

For empty project, execute the command below

```.sh
npx sequelize-cli init
```

create a new database if it does not exist

```.sh
 db:create
```

run migrations

```.sh
npx sequelize-cli db:migrate
```

undo most recent migrations

```.sh
npx sequelize-cli db:migrate:undo
```

undo all migrations

```.sh
npx sequelize-cli db:migrate:undo:all
```

> You can also revert back to a specific migration by passing its name with the `--to` option

The above information from official sequelize docs

> https://sequelize.org/docs/v6/other-topics/migrations/
