# Identicon

This is a console based application that will return an image. This image will be created based on a given string as input for the `main` function.

The image creation is arbitrary, but, since it uses a string (actually, it uses the string [MD5 hashing](https://en.wikipedia.org/wiki/MD5) if you input the same exact string over and over again, it will return the same image.

This application was created following [The Complete Phoenix and Elixit Bootcamp](https://www.udemy.com/course/the-complete-elixir-and-phoenix-bootcamp-and-tutorial) course at Udemy.

## Use

You will need Elixir installed to run this command-line application. Follow the instructions [here](https://elixir-lang.org/install.html), it's very easy :)

After installing Elixir, follow this steps:

Clone this repo
`git clone https://github.com/maryplank/identicon.git`

Go into the Identicon folder

`cd identicon`

Install the dependecies

`mix deps.get`

Start the elixir REPL

`iex -S mix`

Run the function main and provide as input the string you want to see transformed in an image!

```
iex > Identicon.main("banana")
:ok
```

The return will be `:ok` and you will find a `.png` file with the string you provided as a name at the identicon directory.


Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).

