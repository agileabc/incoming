# incoming

* https://addyosmani.com/resources/essentialjsdesignpatterns/book/
* https://leanpub.com/understandinges6/read
* https://library.epam.com/
* http://wwsun.github.io/

To Do
-----
* 了解http://jasmine.github.io/ 的工作原理。
* 了解mocha的各项工作方法。
* Cross Domain: https://jvaneyck.wordpress.com/2014/01/07/cross-domain-requests-in-javascript/

Done
----
* 使用Mocha如何测试DOM的构建结果? Done. 

{
  "name": "watchlist",
  "version": "0.0.1",
  "description": "Watchlist HTML Client",
  "directories": {},
  "main": "dist/watchlist.js",
  "url": "https://github.ldn.swissbank.com/FedAnaly/watchlist",
  "repository": {
    "type": "git",
    "url": "git@github.ldn.swissbank.com:FedAnaly/watchlist-html-client.git"
  },
  "license": "UBS-Internal-Only",
  "scripts": {},
  "browserify-shim": {
    "d3": "global:d3",
    "ubs-neo": "global:ubs.neo",
    "ubs-grid": "global:ubs.grid",
    "instrument-lookup": "global:ubs.instrumentLookup"
  },
  "devDependencies": {
    "babel-core": "^6.3.17",
    "babel-eslint": "^4.1.5",
    "babel-preset-es2015": "^6.1.18",
    "babelify": "^7.2.0",
    "browserify": "^12.0.1",
    "browserify-shim": "^3.8.11",
    "grunt": "^0.4.5",
    "grunt-browserify": "^4.0.1",
    "grunt-cli": "^0.1.13",
    "grunt-contrib-clean": "^0.6.0",
    "grunt-contrib-cssmin": "^0.12.3",
    "grunt-contrib-less": "^1.0.1",
    "grunt-contrib-uglify": "^0.9.1",
    "grunt-contrib-watch": "^0.6.1",
    "grunt-eslint": "^17.3.1",
    "lodash": "^3.10.1",
    "mocha": "^2.3.4",
    "node-underscorify": "0.0.14",
    "object-assign": "^4.0.1",
    "websdk-colours": "^3.1.0"
  }
}
