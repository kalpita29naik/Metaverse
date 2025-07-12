## Requirements

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Sass](https://sass-lang.com/install) (Install globally)

  ```bash
  npm install -g sass
  ```

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd Metaverse
   ```

3. Install dependencies:
   ```bash
   npm install
   ```
4. Compile Sass to CSS:
   ```bash
   sass scss/main.scss css/main.css
   ```
5. Open `index.html` in your web browser to view the project.

6. To watch for changes in Sass files and automatically compile, run:
   ```bash
   sass --watch scss/main.scss:css/main.css
   ```
