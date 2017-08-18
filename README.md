Add new conan remote:
```
conan remote add pony-test https://api.bintray.com/conan/hardliner66/test
```

build with:
```
conan install --build
python build.py
```