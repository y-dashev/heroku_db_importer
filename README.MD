Ruby script so for importing heroku PG database to a project.
                               

In case you are using the 'fish' terminal you need to add the function with the path to the script
Like so:

```
function pg_db_import # or you can name it as you want 
  [$your absolute path to - pg_db_import.rb] $argv
end
```

Then you can use the script to get the heroku db  and hook it with the local one :) 
STILL NEEDS TO BE TESTED!

example usage: 

```
// In your root folder
rubycode --app_name "[APPNAME]" --db_name '[LOCAL_DB_NAME]'  -u '[LOCAL USERNAME][OPTIONAL]'
```
