# Identikon

**Utility: Creates an Identicon for a given name. Identicons are images
generated for a given name. Like the default avatar assigned by Github when you
sign up.**

**To Run:**

```
iex> Identikon.main("llk23r")
```

The above code will generate an image as:

![alt identicon](llk23r.png)


```
iex> Identikon.main("bitcoin")
```

The above code will generate an image as:

![alt identicon](bitcoin.png)



## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identikon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identikon, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identikon](https://hexdocs.pm/identikon).

