# f0-extraction

wavからピッチを取り出すだけ

librosaが更新死んでいたり、pyworldだとキレイに取れなかったので[audioflux](https://audioflux.top/mir/pitch.html)を試した

PitchYINではダメだったが、PitchPEFで割と綺麗に取れた

サンプルコードの時点で書き味がなんか違和感すごいけどほぼ写経で動いたのでヨシ

## 動かす方法

rye syncしてsrc/f0_extract.ipynbの中を適当にいじって動かす
assetフォルダーは.gitignoreしている