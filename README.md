# jokcolor

[Janet](https://janet-lang.org) bindings to [Okhsv and Okhsl](https://bottosson.github.io/posts/colorpicker).
The source code for the API has been obtained from [here](http://bottosson.github.io/misc/ok_color.h) and
adapted to a C header. The bindings are a 1 to 1 mapping of the original API, but function names are lispified.

## Example

```janet
(use jokcolor)

(okhsl-to-srgb [0.5 0.5 0.5])
```
