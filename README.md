# roslibjs-intellisense
Adds roslibjs and jQuery to VS Code IntelliSense

## Installation
1. Move to your project root.

2. Clone this repository as a submodule named `node_modules` in your project root:
   ```
   git submodule add https://github.com/jkhamanishi/roslibjs-intellisense.git node_modules
   ```
3. If this is the first submodule in your project, it will create a `.gitmodules` file. Don't forget to commit this.

4. That's it! IntelliSense will now show roslibjs and jQuery details.

## Git Submodule Tips
Next time you clone you project, you can also clone this repo with it by adding the `--recurse-submodules` flag.
```
git clone --recurse-submodules <ProjectURL>
```

If your project is already cloned and updated with this repo, but the `node_modules` folder is empty, you can initialize all your submodules with the following command in your project root:
```
git submodule update --init --recursive
```
