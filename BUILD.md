### Developing
Install dependencies with:
```lang=bash
pnpm install
```
This will install all the needed dependencies.


#### Running web-server
Just run `pnpm start` to start the web server and the livereload task.
Open http://localhost:8080/ in your browser.


#### Running in production

Run `node build` to build the minimized production version of the app. Copy `public` folder contents to your web server.