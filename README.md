# express_benchmark
* node v4.2.3
* express 4.13.3

```
$ node app.js

$ wrk -t4 -c100 -d30S --timeout 2000 "http://127.0.0.1:3000"
```
