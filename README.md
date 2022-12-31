### Development Environment

- Laravel Framework 8.83.27
- PHP 8.1.1
- Composer 2.2.4
- Node 18.12.1
- Npm 9.2.0


### Deployment Environment

- Ubuntu
- NginX
- MySQL
- IPAddress


### URL pattern Convention

- /resource/action/id
- /resource/action/id/sub-resource/sub-action


### Naming Conventions

- Controllers shoud be CapitalCase because of Class Name and are also no spacing between words, and end with "Controller". (e.g, ArticleController, Comment Controller).
-Migrations and Models also shoud be CapitalCase, and no need to end with any word behind it.(e.g, Article, Comment).
Namespace only uses CapitalCase and no extension name.
In Laravel Framwork, Class autoload is used instead of include().
- Variables should typically be in snake case because all table columns are snake_case. (i.e. user_posts).
- Methods methods should be camelCase but the first character lower case and should     start with verb . (i.e. getAllUsers)
- Blade files should be in lower case, snake_case (underscore between words). (i.e. all.blade.php, all_posts.blade.php)
- DB tables should be in lower case, with underscores to separate words (snake_case),   and should be in plural form. (i.e. posts, project_tasks)
- Pivot tables should be all lower case, each model in alphabetical order, separated by an underscore (snake_case). (i.e. post_user, task_user )
- Table column should be in lower case, and snake_case (underscores between words). It shouldn't be referenced the table name.
- Primary Key This should normally be id.
- Foreign keys should be the model name (singular), with '_id' appended to it (assuming the PK in the other table is 'id').