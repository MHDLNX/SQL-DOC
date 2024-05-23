### `drop database <name>` : remove database completely and all of it's contents 

### `use <database name>` : use a database
  we can think of it as double clicking on this database . selecting as what we want to be working inside of . 
  The `USE` command in SQL is employed to select a particular database in which you want to perform operations such as queries, updates, or schema modifications. When you have multiple databases within your SQL server, the `USE` statement is essential to switch context to the specific database you intend to work with. 

### Syntax

The basic syntax of the `USE` command is straightforward:

```sql
USE database_name;
```

### Example

Suppose you have multiple databases named `sales_db`, `inventory_db`, and `hr_db`. If you want to run queries on the `inventory_db` database, you would use the following command:

```sql
USE inventory_db;
```

### Key Points

1. **Context Switching**: After executing the `USE` command, all subsequent SQL statements are executed within the context of the selected database.
2. **Session-Specific**: The effect of the `USE` command is session-specific, meaning it only applies to the current session. If you open a new session, you need to issue the `USE` command again if you want to work with a different database.
3. **Permissions**: You must have the necessary permissions to access and switch to the specified database. Without proper permissions, the `USE` command will fail.
4. **Database Name**: The `database_name` should be correctly spelled and must exist within the SQL server instance; otherwise, an error will be thrown.
<hr>

## to see which database you're currently in ==> `select database()`

