# CUHK Thesis Template

## Usage

Since we need to process Chinese characters, please use LuaTex to compile the document.

```bash
lualatex main && biber main && lualatex main && lualatex main
```

or

```bash
# make sure that 'compile' has the execution permission (chmod +x compile)
./compile
```

### Font
If missing font issues happen during the whole project compilation, please manually check whether the font 'STFangsong' is installed. If you are using MacOS, the font should be found within '/Library/Fonts/'. If not, please install it manually.

```bash
export OSFONTDIR="$HOME/FontExplorer X/Font Library//"
luaotfload-tool --update
luaotfload-tool --find="STFangsong"
```

## License

MIT License.
