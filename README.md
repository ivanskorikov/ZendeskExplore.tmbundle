# Zendesk Explore Syntax Highlighting

A TextMate bundle that provides syntax highlighting for Zendesk Explore formulas. Instead of writing large formulas in the browser, you can use your favorite TextMate-capable editor to get syntax highlighting. To use, save your formula to a file with any of these extensions:
- `.zd`
- `.zendesk`
- `.explore`

![](https://i.postimg.cc/sfhbvHPC/image.png)

## Features

- **Syntax Support**: Highlights Zendesk Explore formula elements
- **Function Recognition**: Supports all functions listed in [Explore function reference](https://support.zendesk.com/hc/en-us/articles/4408834558746-Explore-functions-reference)
- **Operator Highlighting**: Arithmetic, comparison, and logical operators
- **Comment Support**: Supports multi-line (`/* */`) comments
- **String & Number Literals**: Highlighting for quoted strings and numeric values


## Installation

### Sublime Text

Sublime Text requires manual installation of the syntax and theme files.

1. **Open Packages Directory**:
   - In Sublime Text, go to `Preferences` → `Browse Packages...`
   - This opens your Sublime Text packages folder

2. **Create Zendesk Explore Directory**:
   ```bash
   mkdir "Zendesk Explore"
   cd "Zendesk Explore"
   ```

3. **Copy Syntax Files**:
   - Copy `Zendesk Explore.tmLanguage` from `Zendesk Explore.tmbundle/Syntaxes/` to the new directory
   - Copy `Zendesk Explore.tmTheme` from `Zendesk Explore.tmbundle/Themes/` to the new directory

   ```
   Packages/
   └── User/
       ├── ...
       ├── Zendesk Explore.tmLanguage
       └── Zendesk Explore.tmTheme
   ```

4. **Restart Sublime Text** (optional)

5. **Open** a `.zd`, `.zendesk` or `.explore` file to see the syntax highlighting

6. **Apply Theme** (optional):
   - Go to `Preferences` → `Color Scheme`
   - Select "Zendesk Explore" from the list

### JetBrains IDEs (IntelliJ IDEA, PyCharm, WebStorm, etc.)

JetBrains IDEs have built-in support for TextMate bundles through the TextMate Bundles plugin.

1. **Enable TextMate Bundles Plugin** (usually enabled by default):
   - Open Settings (`Ctrl+Alt+S` on Windows/Linux, `Cmd+,` on macOS)
   - Go to `Plugins` → `Installed`
   - Ensure "TextMate Bundles" is enabled

2. **Import the Bundle**:
   - Navigate to `Settinga` → `Editor` → `TextMate Bundles`
   - Click the `+` (Add) button
   - Browse to and select the `Zendesk Explore.tmbundle` folder
   - Click `OK` to apply changes

3. **Verify Installation**:
   - Open a `.zd`, `.zendesk` or `.explore` file or create a new file with Zendesk Explore formula
   - The syntax highlighting should automatically activate

## Author

Ivan Skorikov (ivanskorikov@github)

---

**Note**: This bundle is not officially affiliated with Zendesk. It's a community-created tool to improve the development experience when working with Zendesk Explore formulas.
