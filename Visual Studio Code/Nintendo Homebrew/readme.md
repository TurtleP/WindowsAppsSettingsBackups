## Configurations for Nintendo Homebrew Compilation

The file `c_cpp_configuration.json` contains configurations for Nintendo 3DS and Switch homebrew. This helps with intellisense. Simply create `.vscode/c_cpp_configuration.json` in your project directory and then copy and paste the content from this repo's file in there.

### Notes

However, if you only require one of the configurations (especially if you don't need the debug), simply copy the configuation's length via its curly brackets `{}` and ensure there's no stray commas. Copy this empty template, then paste the configuration inside of it:

```json
{
    "configurations":
    [
        // paste here
    ]
}
```
