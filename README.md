# Identicon

### Steps to run the app

```shell
  > Mix deps.get
  > iex -S mix

  Erlang/OTP 22 [erts-10.7.2.1] [source] [64-bit] [smp:8:8] [ds:8:8:10] [async-threads:1] [hipe]

  Interactive Elixir (1.9.2) - press Ctrl+C to exit (type h() ENTER for help)
  iex(1)> Identicon.main("your name")
  :ok
  iex(2)>
```

**Identicon with "your name" will be ceated and stored inside the media folder**

### Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).
