# My 4 Favorite Ruby methods

### `zero?`

Returns a `true` boolean if the `Float` returns 0. Otherwise, it returns `false`.

```ruby
0.0.zero? #=> true
3.829.zero? #=> false
```

### `next_year`

This method is called on a Ruby `Date` object and it returns that date one year in the future.

```ruby
Date.new(2014, 8, 9).next_year #=> #<Date: 2015-08-09 ...>
```

It optionally takes an argument that increments the new date by the `Integer` it is given.

```ruby
Date.new(2006, 12, 3).next_year(3) #=> #<Date: 2009-12-03 ...>
```

### `.nil?`

This method can be called on any Ruby `Object` and returns a boolean if that object is `nil` or not.

```ruby
"string".nil? #=> false
0.nil? #=> false
Object.new.nil? #=> false
nil.nil? #=> true

variable = nil
variable.nil? #=> true
```
