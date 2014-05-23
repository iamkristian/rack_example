# Rack Example

The simplest rack example

# Installation

As always run

```
bundle install
```
to install it.

# Running it

Using the basic rackup you can do

```
rackup config.ru
```

Using [puma](http://puma.io) you can do
```
puma config.ru
```

Using the params @evanphx was so kind to share in his talk
```
puma -q -t 10 -w 4 config.ru
```
Which will spawn 4 workers with 10 threads.

