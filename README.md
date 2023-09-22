# MacOS Ruby on Rails Setup

Sets up a Mac for Ruby on Rails development.

## Usage

```
./setup
```

## After setup

### Create a new Rails app

```
rails new --minimal myapp
cd myapp
```

### List Rake tasks

```
rails -T
```

### Run the Rails application

```
rails server
```

### Set the Ruby version for a project

Create a `.ruby-version` file:

```
❯ cat .ruby-version
ruby-3.2.2
```

Use `frum` to set the current Ruby version:

```
frum local
```

## References

- [Install Ruby on Rails 7 · macOS](https://mac.install.guide/rubyonrails/index.html)
- [Install Ruby with Frum](https://mac.install.guide/ruby/14.html)
- [A Comparison of Ruby Version Managers for macOS](https://www.sitepoint.com/ruby-version-managers-macos/)
- [How to install PostgreSQL on a Mac with Homebrew](https://www.moncefbelyamani.com/how-to-install-postgresql-on-a-mac-with-homebrew-and-lunchy/)
