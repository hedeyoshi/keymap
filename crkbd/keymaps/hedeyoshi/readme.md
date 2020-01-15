# hede's crkbd Layout mac

ベースは default。

-   アローキーを入れた代わりに F17 ～ 20 はトルツメ。
-   raise + del -> backspace
-   win mac を入れた

## ビルドのコード

```
cd qmk_firmware

make crkbd:hedeyoshi

make crkbd:hedeyoshi:avrdude
```
