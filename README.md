# Electron Boilerplate
Boilerplate for developing Electron apps using TypeScript2.x and ReactJS.

## Usage

1. Clone this repository:

	```bash
	$ git clone https://github.com/rose-m/electron-react-ts-boilerplate.git
	```

2. Go to repository folder:

	```bash
	$ cd electron-react-ts-boilerplate
	```

3. Install dependencies:

	```bash
	$ npm install
	```

4. Build demo app:

	```bash
	$ gulp
	```

5. Run demo app:

	```bash
	$ npm start
	```
   or
   ```bash
   $ electron .
   ```

6. During development you can also run

    ```bash
    $ gulp watch
    ```
    
    which will watch your resources, styles, and scripts and recompile on changes. Furthermore, this
    does not do minification for easier debugging.

## Structure

```
├── app/
│   ├── components/
│   ├── resources/
│   ├── styles/
│   └── app.tsx
├── devtools/
│   └── react/
├── .gitignore
├── gulpfile.js
├── package.json
├── tsconfig.json
├── index.pug
└── main.ts

```

#### [app/](https://github.com/rose-m/electron-react-ts-boilerplate/tree/master/app)

Contains ReactJS application.

#### dist/

Output directory for build process.

#### [devtools/](https://github.com/rose-m/electron-react-ts-boilerplate/tree/master/devtools)

Contains 3th party extensions for development.

#### [tsconfig.json](https://github.com/rose-m/electron-react-ts-boilerplate/blob/master/tsconfig.json)

Configuration file for TypeScript project.

#### [index.pug](https://github.com/rose-m/electron-react-ts-boilerplate/blob/master/index.pug)

Frontend entry point of application.

#### [main.ts](https://github.com/rose-m/electron-react-ts-boilerplate/blob/master/main.ts)

Backend entry point of application.

## License

[MIT License](https://github.com/rose-m/electron-react-ts-boilerplate/blob/master/LICENSE.md)
