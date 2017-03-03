# Watch File Change 
Any change in file which is dependency with entry.js, which trigger ...

# Run
```
$ webpack --watch

or 

$ webpack -w

Webpack is watching the files…

Hash: f17dfb04f57f26f00675
Version: webpack 2.2.1
Time: 65ms

// After edited some file

      Asset     Size  Chunks             Chunk Names
./bundle.js  2.67 kB       0  [emitted]  main
   [0] ./content.js 46 bytes {0} [built]
   [1] ./entry.js 41 bytes {0} [built]
```