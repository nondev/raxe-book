# Null

The Null type has only one possible value:

```haxe
null
```

When explicitly specifying type as null-able, you should use it with `Null[T]` syntax

```ruby
def string : Null[String] = null
def bool : Null[Bool] = null
def int : Null[Int] = null
```