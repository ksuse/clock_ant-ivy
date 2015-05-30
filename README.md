# アナログ時計

## 依存ライブラリ

* [args4j](http://args4j.kohsuke.org)
    * コマンドラインオプション解析ライブラリ

## 使用方法

```
java -jar clock.jar [OPTIONS]

  -d (--debug)                : debug mode. (default: false)
  -h (--help)                 : print this message and quit. (default: false)
  -hh (--more-help)           : print detail help message. (default: false)
  -tz (--timezone) <TIMEZONE> : Specifies time zone. Default is local time.
  -v (--version)              : show version. (default: false)
```

## タイムゾーン

-tz オプションで時計のタイムゾーンを指定できます．
利用可能なタイムゾーンは，--more-help オプション(-hh)で閲覧できます．

## コンパイル方法

1. antを実行する．

## その他．

このプロジェクトをコンパイルするには，[apache ivy](http://ant.apache.org/ivy/)のインストールが必要です．
また，ivy-x.x.x.jar を ant の lib もしくは，~/.ant/lib 以下にコピーしておく必要があります．


