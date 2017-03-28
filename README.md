# Initial layout with Gulp configuration

It is being used for Gulp tasks:
- Development server configuration
- Compile stylus
- Add prefixes for compatibility with different browsers
- JSHint to scan files Javascript
- Minimize CSS and Javascript files
- Multidevice synchronization client for testing

The configuration of the paths are in the file `config.json`

--------------------------------------------------------------
## How to use?
- Instal NodeJS and clone the repository
- Install gulp globally: `npm install gulp -g`
- Install dependencies for the project: `npm install`
- Run server: `gulp serve`
- You could access to development server: `http://localhost:3000`
- You could access to browsersync area: `http://localhost:3001`
- To generate files for deploy: `gulp build`
