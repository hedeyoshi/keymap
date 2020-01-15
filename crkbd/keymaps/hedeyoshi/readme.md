# hede's crkbd Layout mac&windows

ベースは default。

-   アローキーを入れた代わりに F17 ～ 20 はトルツメ。
-   raise + del -> backspace
-   win mac を入れた
-   ボリュームの上下を追加した

## ビルドのコード

```
cd qmk_firmware

make crkbd:hedeyoshi

make crkbd:hedeyoshi:avrdude
```
