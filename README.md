# ChunItachi

ChunItachi is an injectable dll for Chunithm Amazon which enables KamaItachi uploads

## Installation & Usage

Make sure you have [Microsoft VC++ Runtimes](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads) installed.

Modify your start.bat to mirror:

```bash
inject -d -k chunihook.dll -k ChunItachi.dll chuniApp.exe
```

Place ChunItachi.dll in your app/bin directory.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)