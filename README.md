> "Beautiful Soup is a library that makes it easy to scrape information
> from web pages. It sits atop an HTML or XML parser, providing Pythonic
> idioms for iterating, searching, and modifying the parse tree."

This is an extension of the original BeautifulSoup v4.6.3 that extends the `NavigableString` object
with `.start_position` and `.end_position` attributes, that will return the string indices where the underlying `NavigableString` elements start and end.
The goal is to replicate the extension made for JSoup by Thijs Vogels (https://github.com/tvogels/jsoup).

While, other than these two added values, this is an exact replica of BS4.6.3, I recommend against using this repository. It is mainly here for `pip install`  referencing. It will **not** be maintained often in the future, unless a very significant BeautifulSoup update is released.