# Ajax - Refactor


Live demo: N/A Heroku not playing nice on Windows

![Alt Text](https://gyazo.com/e861fb0d8dfe248d342346f58291c6e0.gif)
![Alt Text](https://gyazo.com/1e2ee2efc9b62b7087c34efaac57045e.gif)

### Installation
```
Open Terminal
```

```
$ git clone https://github.com/NickoDelaCruz/refactor-ajax.git
```

## How To Run

Install gems

```
$ bundle update
```

Create DB

```
$ rake db:create
```

Migrate DB

```
$ rake db:migrate
```



## Refactored Code

- [x] Add ability so users can remove items from cart without reloading page
- [x] Add AJAX when adding products to shopping cart
- [x] Add quantity of items in nav bar updates without reloading page
- [x] Add order Item model includes a validation (no negative numbers)
- [x] Add 1 - 50 character inputs
- [x] Add Flash message appears after successful sign-in/sign-out
- [x] Add Flash message appears after successful registration
- [x] Add Flash message appears after user attempts to add product without admin rights
- [x] Add validations for product name and description to product class
- [x] Fixed the row height for products (iffy)
- [x] Refactored Navbar
- [x] Additional styling
- [ ] Users can click a product name on the products index to show its details at the top of the page. (no time)
- [ ] Add integration testing for AJAX functionality


## Seeding DB w/ Faker

To populate db using Faker Gem run:


```
$ rake db:seed
```

## Testing
Before running rspec:
```
$ rake db:schema:load RAILS_ENV=test

```

and then:

```
$ bundle exec rake db:migrate

```


Run Test:
```
$ rspec
```

## Bugs

Styling conflits with some messages (will make it prettier)

## Built With

* [Atom](https://atom.io/) - Text editor
* [cmder](http://cmder.net/) - Windows terminal
* [Ruby](http://railsinstaller.org/en) - Ruby on Rails
* [Postgres](https://www.postgresql.org/download/) - Postgres




## Authors

* **Nicko Dela Cruz**  [Epicodus Github](https://github.com/NickoDelaCruz)



## License

OS
