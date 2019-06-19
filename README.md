## Install rbenv
```
$ brew install rbenv
$ vi ~/.bashrc
+ export PATH="$HOME/.rbenv/bin:$PATH"
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

## Create Hello App
```
bundle exec rails _5.1.6_ new hello_app
```
