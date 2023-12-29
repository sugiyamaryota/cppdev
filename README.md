https://qiita.com/yuzutarogo/items/8898377739b5c674743f

```zsh
# コンテナに入る
docker container exec -it cppdev /bin/sh

# コンテナに入った後、実行
cd /cppdev/src
g++ hello.cpp -o hello
./hello
# Hello! World!
```