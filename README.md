## Install rbenv
```
$ brew install rbenv
$ vi ~/.bashrc
+ eval "$(rbenv init -)"
$ source ~/.bashrc
```

## Change ruby version
```
$ rbenv install 2.6.3
$ rbenv local 2.6.3
```

## Install rails 5.1.6
```
$ bundle install
$ bundle exec rails -v
```

## Rails CLI
```
# create new application
rails _5.1.6_ new hello_app

# generate scaffold
rails generate scaffold User name:string email:string
rails generate model User name:string email:string
rails generate controller StaticPages home help

# destroy controller
rails destroy model User
rails destroy controller StaticPages home help

# migrate database
rails db:migrate

# rollback database
rails db:rollback

# rollback to initial version
rails db:migrate VERSION=0

# Run console
rails console

# Run test
rails test
```

### Shortcut
| Full command | Shortcut |
----|---- 
| `rails server` | `rails s` |  
| `rails console` | `rails c` |  
| `rails generate` | `rails g` |  
| `rails test` | `rails t` |  
