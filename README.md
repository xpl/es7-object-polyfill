# A polyfill for missing Object.values / Object.entries

Installing:

```bash
npm install es7-object-polyfill
```

Usage:

```javascript
require ('es7-object-polyfill')
```

It will automatically create `Object.values` and `Object.entries` — but only if they're not already defined.