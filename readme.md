# Install
* npm install

# Build
* npm run prod

# Execute
* test.exe

# Result
```
pkg/prelude/bootstrap.js:1359
      throw error;
      ^

Error:
Something went wrong installing the "sharp" module

The specified module could not be found.
C:\Users\Morris\AppData\Local\Temp/261f324a7928e129326f8f11568d52b892f79d7e9d46fae48e6c17f24ea3fa9f_sharp.node

- Remove the "node_modules/sharp" directory then run
  "npm install --ignore-scripts=false --verbose sharp" and look for errors
- Consult the installation documentation at https://sharp.pixelplumbing.com/install
- Search for this error at https://github.com/lovell/sharp/issues

    at Object.<anonymous> (C:\snapshot\pkgsharptest\node_modules\←[4msharp←[24m\lib\constructor.js:32:9)
    at Module._compile (pkg/prelude/bootstrap.js:1433:22)
←[90m    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1218:10)←[39m
←[90m    at Module.load (internal/modules/cjs/loader.js:1047:32)←[39m
←[90m    at Function.Module._load (internal/modules/cjs/loader.js:935:14)←[39m
←[90m    at Module.require (internal/modules/cjs/loader.js:1087:19)←[39m
    at Module.require (pkg/prelude/bootstrap.js:1338:31)
←[90m    at require (internal/modules/cjs/helpers.js:73:18)←[39m
    at Object.<anonymous> (C:\snapshot\pkgsharptest\node_modules\←[4msharp←[24m\lib\index.js:3:15)
    at Module._compile (pkg/prelude/bootstrap.js:1433:22)
PS C:\xampp\htdocs\pkgsharptest>
```
