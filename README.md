[![Stories in Ready](https://badge.waffle.io/Pizza-King/ring-the-king.png?label=ready&title=Ready)](https://waffle.io/Pizza-King/ring-the-king?utm_source=badge)
# Pizza King | Ring The King Application

This is a development application for
[*Pizza King Indiana:
Ring The King Website*](http://www.ringtheking.com/)
by [Dustin Armstrong](http://www.dustinarmstrong.info/).

## License

All source code is based off of the [Ruby on Rails Tutorial](http://railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book).
