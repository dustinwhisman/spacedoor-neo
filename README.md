# Spacedoor

This is a super basic site to host Spacedoor rules and character sheets, intentionally made without any build tools to keep it simple. All the files needed for the site live in the `dist` folder.

## Running a local server

There's no back-end, since everything is stored client-side in `localStorage`, but to run it locally for development/testing, you'll need to [run a local server](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/set_up_a_local_testing_server).

### Node.js

If you have [Node.js](https://nodejs.org/) installed, you can use [`http-server`](https://www.npmjs.com/package/http-server) to spin up a local server.

```sh
# check whether node is installed
node -v

# run a local server against the dist folder
npx http-server dist
```

### Python

If you have [Python](https://www.python.org/downloads/) installed, you can use its built-in `http.server` module.

```sh
# check whether Python is installed
python -v

# or maybe Python 3
python3 -v

# navigate to the dist directory
cd dist

# run a local server in the current directory
python -m http.server
```
