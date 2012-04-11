# Redis Viewer
Simple browser-based admin for redis

## Installation

1. `git clone git@github.com:tblobaum/redis-viewer.git`
2. `cd redis-viewer/`
3. `npm install`
4. `node server.js`

## Notes
Since this is intended to be a development tool there are a few caveats:

* the default command is `KEYS *` which could cause performance issues if you have a lot of keys
