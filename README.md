# Webpack 2 - Hot Module Replacement for CSS

Learn how to setup Webpack 2 and hot reload your CSS or SASS.

## Webpack 2 Playlist

[Watch on YouTube](https://www.youtube.com/watch?v=JdGnYNtuEtE&list=PLkEZWD8wbltnRp6nRR8kv97RbpcUdNawY)

## How to use the files?

1. Clone this repo
2. Run `npm install` to install all the dependencies
3. Run `npm run dev` for development mode
4. New browser window should open automatically.

## Notes

### 1. Issue with Pug HTML Loader
If you are having issues with [pug-html-loader](https://www.npmjs.com/package/pug-html-loader), try to install [pug-loader](https://github.com/pugjs/pug-loader) and change the loader inside of package.json to `use: 'pug-loader'`. That should fix it.

Or simply remove pug template and use pure html.

### 2. Issue with NODE_ENV on PC
If you are on pc you will need to type the word `SET` before the NODE_ENV in package.json.

`"prod": "npm run clean && SET NODE_ENV=production webpack -p"`

Don't forget to [subscribe to my channel](https://www.youtube.com/channel/UC7O6CntQoAI-wYyJxYiqNUg?sub_confirmation=1) for more front-end videos.
