## Syntax Highlighting
A module originally found on the Devforum, ported to support exploit needs using loadstring() instead of require.

## Usage

Importing the library
```lua
local module = loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/hello-n-bye/textbox-syntax/main/highlighter.lua"))()
```

## Applying to a TextBox

```lua
local module = loadstring(game:HttpGetAsync("..."))() -- Replace the url with the correct one.

module.highlight({
  textObject = script.Parent -- A LocalScript inside of your TextBox
})
```

## Proper Credits

Checkout the [original author's repository](https://github.com/boatbomber/Highlighter) here.
<br>Original code by [BoatBomber](https://github.com/boatbomber), ported to exploits by [me](https://github.com/hello-n-bye).
