## mySQL

### create a new database with UTF-8

```sql
CREATE DATABASE $databaseName CHARACTER SET utf8 COLLATE utf8_unicode_ci;
```

### create user with the password correctly

```sql
CREATE USER $username@$hostname IDENTIFIED WITH mysql_native_password BY $password;
```

### grant all privileges on database to user

```sql
GRANT ALL ON $databaseName.* to $username@$hostname;
```

### update user password

```sql
ALTER USER $username@$hostname IDENTIFIED WITH mysql_native_password BY $password;
```
