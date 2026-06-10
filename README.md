# Tailwind editor setup

To remove yellow underlines for Tailwind classes in VS Code, follow these steps:

1. Install the **Tailwind CSS IntelliSense** extension by Tailwind Labs.
2. Reload VS Code (Developer: Reload Window).
3. If warnings persist, ensure this workspace has the following files:
   - `.vscode/settings.json` (disables built-in CSS validation as a fallback)
   - `tailwind.config.js` (this file)

These files are already present in this workspace. After installing the extension and reloading, the editor will correctly recognize Tailwind arbitrary and bracketed classes and the yellow underlines should disappear.
