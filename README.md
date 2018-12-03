### istanbul
---
https://github.com/gotwarlost/istanbul

```
npm install -g istanbul
cd /path/to/your/source/root
istanbul cover test.js
istanbul help
istanbul cover my-test-script.js -- my test args
```

```js
var istanbul = require('istanbul');
var instrumenter = new istanbul.Instrumenter();
var generatedCode = instrumenter.instrumentSync('function meaningOfLife() { return 42; }',
  'filename.js');

var istanbul = require('istanbul');
  collector = new istanbul.Collector(),
  reporter = new istanbul.Reporter(),
  sync = false;
collector.add(obj1);
collector.add(obj2);
reporter.add('text');
reporter.addAll([ 'lcov', 'clover' ]);
reporter.write(collector, sync, function(){
  console.log('All reports generated');
});
```

```
```

