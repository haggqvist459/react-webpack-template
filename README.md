## An empty setup ready for new React projects

### Current Webpack config: 
- using compression plugin to compress files into brotli or gzip if brotli is unsupported
- splitChunks into smaller chunks
- separating node_modules & main into own chunks using TerserPlugin
- copy-webpack-plugin copies icons & images from assets/favicon into dist during production build


### Todo: 

- Separate branch with auth components (firebase)

### Completed: 

- DevDependencies
- Webpack configured & good to go
- Basic setup of scss folders & files
- Update scss with new variables for colors
- Other dependencies most often used, e.g. materialUI, react router etc
- Add a list of added dependencies to readme 


#### Dependencies in use: 

- @material-ui/core
- @material-ui/icons
- react
- react-dom
- react-router-dom

#### DevDependencies in use: 

- @babel/core
- @babel/plugin-proposal-class-properties
- @babel/plugin-transform-runtime
- @babel/preset-env
- @babel/preset-react
- babel-loader
- clean-webpack-plugin
- html-webpack-plugin
- copy-webpack-plugin
- compression-webpack-plugin
- css-loader
- file-loader
- sass
- sass-loader
- style-loader
- url-loader
- webpack
- webpack-cli
- webpack-dev-server