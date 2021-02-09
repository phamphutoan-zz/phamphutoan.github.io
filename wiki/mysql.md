## MySQL

### Create a new database with UTF-8

```sql
CREATE DATABASE $databaseName CHARACTER SET utf8 COLLATE utf8_unicode_ci;
```

### Create user with the password correctly

```sql
CREATE USER $username@$hostname IDENTIFIED WITH mysql_native_password BY $password;
```

### Update user password

```sql
ALTER USER $username@$hostname IDENTIFIED WITH mysql_native_password BY $password;
```

### Grant all privileges

```sql
GRANT ALL ON $databaseName.* to $username@$hostname;
```
