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

# generate controller
rails generate controller StaticPages home help

# migrate database
rails db:migrate

# Run console
rails console
```

### Shortcut
| Full command | Shortcut |
----|---- 
| `rails server` | `rails s` |  
| `rails console` | `rails c` |  
| `rails generate` | `rails g` |  
| `rails test` | `rails t` |  
