# Souvik Theme - Installation Guide

## 📦 What You Have

You now have a complete VS Code theme extension with:

- `souvik-theme/` folder - The extension folder

## 🚀 Installation Methods

### Method 1: Copy the Folder (Recommended)

1. **Locate your VS Code extensions folder:**
   - **Windows:** `C:\Users\YourUsername\.vscode\extensions\`
   - **macOS:** `~/.vscode/extensions/`
   - **Linux:** `~/.vscode/extensions/`

2. **Copy the `souvik-theme` folder** to the extensions directory

3. **Restart VS Code** or reload window:
   - Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac)
   - Type "Reload Window" and press Enter

4. **Activate the theme:**
   - Press `Ctrl+K Ctrl+T` (Windows/Linux) or `Cmd+K Cmd+T` (Mac)
   - OR: `Ctrl+Shift+P` → "Preferences: Color Theme"
   - Select "Souvik Theme" from the list

### Method 2: Extract the Zip File

1. **Extract `souvik-theme.zip`** to get the `souvik-theme` folder
2. Follow steps 1-4 from Method 1 above

### Method 3: Install via Command Line

**Windows (PowerShell):**

```powershell
# Navigate to the folder containing souvik-theme
Copy-Item -Path "souvik-theme" -Destination "$env:USERPROFILE\.vscode\extensions\" -Recurse
code --reload-window
```

**macOS/Linux (Terminal):**

```bash
# Navigate to the folder containing souvik-theme
cp -r souvik-theme ~/.vscode/extensions/
code --reload-window
```

## ✅ Verification

After installation, you should see "Souvik Theme" in your theme list:

1. Open Command Palette: `Ctrl+Shift+P` (or `Cmd+Shift+P`)
2. Type "Color Theme"
3. Look for "Souvik Theme" in the dropdown

## 🎨 What Makes This Theme Special

- **Custom Backgrounds:** Carefully selected from your preferred background theme
- **Syntax Colors:** Optimized code highlighting from your preferred color theme
- **Dark Theme:** Easy on the eyes for long coding sessions

## 🔧 Troubleshooting

**Theme doesn't appear:**

- Make sure the folder name is exactly `souvik-theme` (no extra characters)
- Verify the folder is in the correct extensions directory
- Try completely restarting VS Code (close all windows)

**Theme looks broken:**

- Check that `themes/souvik-theme.json` exists in the folder
- Verify `package.json` exists in the root of the extension folder

**Still having issues:**

- Delete the extension folder
- Re-extract or re-copy the souvik-theme folder
- Restart VS Code

## 📝 Customization

Want to tweak colors? Edit `themes/souvik-theme.json`:

- `colors` section: UI backgrounds, borders, etc.
- `tokenColors` section: Syntax highlighting for code

After editing, reload VS Code to see changes.

## 🌟 Enjoy Your Custom Theme!

Your theme is now ready to use. Happy coding! 🎉
