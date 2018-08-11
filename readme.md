# Global installer

`rbenv`とか`nodebrew`でバージョンを変えた時に、
必要なライブラリをいちいち探さなくても一発でインスコできるようにしました。

## Usage

```
$ ./npm-deps-i
$ ./gem-deps-i
```

`$PATH`の配下に移動しても良い（`chmod +x {npm/gem}-deps-i`などをお忘れなく）

## Todo

- バージョンの指定

## Refs

- [Change output](https://stackoverflow.com/questions/5947742/how-to-change-the-output-color-of-echo-in-linux)
- [AirbnbとESLint](https://mae.chab.in/archives/2874)
