A lightweight JSON library for Teal. Inspired by / translated from [rxi's lua library](https://github.com/rxi/json.lua)

### Building and testing
To build from source, run:
```
cyan build
```

To test from source, run:
```
busted -c -m "./build/?.lua"
```

To minify the source code, run:
```
cat json.tl | sed 's/--.*//g' | tr '\n' ' ' | sed 's/  */ /g' > json_minified.tl
```

## License
Original rxi library was MIT licensed. json.tl is licensed under [WTFPL](http://www.wtfpl.net/about/), so just do whatever you want with it (ie, redistribute source code without the license).
