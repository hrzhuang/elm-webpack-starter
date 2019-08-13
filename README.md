# elm-webpack-starter

A minimalist starter for an Elm project bundled using Webpack.

## Attributions

* Usage instructions inspired by that of [elm-community/elm-webpack-starter](https://github.com/elm-community/elm-webpack-starter).
* Placeholder code in src/Main.elm taken from [the official Elm guide](https://guide.elm-lang.org).

## Prerequisites

* npm

## Usage

1. Clone this repository.

   ```bash
   # Replace "my-elm-project" with your own project name
   git clone https://github.com/hrzhuang/elm-webpack-starter my-elm-project
   cd my-elm-project
   ```

2. Remove the .git directory from this repostory.

   **Mac, Linux, or any other UNIX-like operating system**
   
   ```sh
   rm -rf .git
   ```
   
   **Windows**
   
   ```bat
   rmdir .git /s /q
   ```

3. Initialize a new repository for your project if you want one.

   ```sh
   git init
   git add -A
   git commit -m "Initial commit"
   ```

4. Install NPM dependencies.

   ```sh
   npm install
   ```

5. Now you can:

   * `npm start` to start a development server.
   * `npm run build` to build for production.
