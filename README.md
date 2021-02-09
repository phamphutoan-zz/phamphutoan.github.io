### Hi there 👋, I'm Toan

- 🔭 e-Commerce Engineer at [Gameloft](https://www.gameloft.com/en/).
- 🤔 Software Engineer at [UIT - Vietnam National University](https://en.uit.edu.vn/).
- 🌱 I’m currently learning about [Golang](https://golang.org/).
- 💬 Ask me about web service, system/database design & analysis, SQL/MDX query.
- 📫 How to reach me: [eMail](mailto:phamphutoan98@gmail.com).
- 😄 Pronouns: He/Him.
- ⚡ Fun fact: There is no trash programming language so don't trash your resources.

### A little more about me...

```php
<?php

$toan = [
    'pronouns' => 'He' || 'Him',
    'programmingLanguages' => ['PHP', 'Javascript', 'Python', 'C/C++', 'Go'],
    'advanced' => ['web service', 'system/database design & analysis', 'SQL/MDX query'],
    'frameworks' => ['Laravel', 'Vue', 'Angular', 'Apache Spark', 'NestJS'],
    'ops' => ['Docker', 'CI/CD', 'LAMP stack'],
    'misc' => ['Gitflow', 'SCRUM', 'SOLID'],
];

$futureGoals = ['advanced Go', 'machine learning'];

$current = [
    'city' => 'Ho Chi Minh',
    'company' => 'Gameloft',
    'position' => 'e-Commerce Engineer',
    'activity' => 'implement multinational mobile e-Commerce & distributed systems',
];

$futureGoals = array_filter($futureGoals, function (string $goal) use (&$toan, $current) {
    echo $current['activity'] . PHP_EOL;
    echo 'learning ' . $goal . PHP_EOL;
    $toan['advanced'][] = $goal;
    echo 'contribute to open source' . PHP_EOL;
    return false;
});

echo 'let\'s get ready for new challenge' . PHP_EOL;
```
### notes

[mySQL](/notes/mysql.md#mysql)
- [create a new database with UTF-8](/notes/mysql.md#create-a-new-database-with-utf-8)
- [create user with the password correctly](/notes/mysql.md#create-user-with-the-password-correctly)
- [grant all privileges on database to user](/notes/mysql.md#grant-all-privileges)
- [update user password](/notes/mysql.md#update-user-password)

[ubuntu](/notes/ubuntu.md#ubuntu)
- [install package via tar.gz](/notes/ubuntu.md#install-via-targz)
- [install package via tar.xz](/notes/ubuntu.md#install-via-tarxz)
