**NOTE:** I later found out [this exists](https://github.com/python/typeshed/tree/master/stubs/beautifulsoup4). But I don't know, maybe this has something typeshed doesn't. But I recommend typeshed's version over this experiment.

# bs4-stubs

[PEP 484 type hint][pep484] [stubs](https://mypy.readthedocs.io/en/latest/stubs.html) for [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) originally generated with [stubgen](stubgen). This is mainly for people who use tools like [MyPy](http://github.com/python/mypy).

# Why

I use BeautifulSoup. I think it's beautiful :ok_hand: :sparkles:.

It's just that mypy gets crazy when I use it (complaining about [Any](https://docs.python.org/3/library/typing.html#typing.Any)). I created this because I couldn't find anything. Some guy wrote [an article explaining BeautifulSoup types](https://skeptric.com/typing-beautiful-soup/) which I will use.

[pep484]: https://www.python.org/dev/peps/pep-0484/
[stubgen]: https://mypy.readthedocs.io/en/latest/stubgen.html

## How to contribute

Please contibute! Mypy's stubgen is flawed and many type annotations needs fixing. The easiest way (as I can think of) is to
 - Run `mypy strict bs4-stubs` on this repo and fix the errors
 - Contribute to this repo when a type annotation needs fixing (e.g. object `x` needs proper type annotation because mypy is ruining my project)
