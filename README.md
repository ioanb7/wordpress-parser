# wp-json-proxy

Simple aggregator and cache layer for a wordpress's `/wp-json` endpoint. This is used in [my blog](https://ioan.blog/).

## Set up:
1. Copy `.env.spec` to `.env` and `.env.dev`
2. Set your two environments up

## To run:
1. Run either `npm run dev` for dev, or `npm run prod` for prod
3. Visit [http://127.0.0.1:4191/all](http://127.0.0.1:4191/all)

## Credits

[cheerio](https://github.com/cheeriojs/cheerio) was helpful library for this project