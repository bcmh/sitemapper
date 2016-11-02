Sitemapper
===

[![Code Climate](https://codeclimate.com/github/bcmh/sitemapper/badges/gpa.svg)](https://codeclimate.com/github/bcmh/sitemapper)

Install
---

```
npm install bcmh/read-sitemap --save
```

Usage
---

```js
const sitemap = require('sitemap');

sitemap('http://example.com/sitemap.xml');
sitemap.fetch();
sitemap.fetchUrls();
//=> ['http://example.com/', 'http://example.com/a']
```


API
---

### sitemap(url)

#### url

Type: `string`

License
---

MIT © [thisislawatts](http://bcmh.build)
