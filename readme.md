# 「幸せのカタチ」本読みアシスタント

演劇「幸せのカタチ」の本読み・稽古用 Web アプリです。

- アプリ: https://kesnonkw.github.io/happy-shape/
- 操作マニュアル: https://kesnonkw.github.io/happy-shape/manual.pdf

## セリフ音声のクレジット

`recordings/hakoi-kata-1023/` のセリフ音声は [VOICEVOX](https://voicevox.hiroshiba.jp/) で生成しています。

| 役 | 音声 |
|---|---|
| 知恵 | VOICEVOX:春日部つむぎ |
| 永遠 | VOICEVOX:冥鳴ひまり |
| 学 | VOICEVOX:白上虎太郎 |
| 父 | VOICEVOX:青山龍星 |
| 母 | VOICEVOX:九州そら |

アプリ内で誰かが録音したセリフは、合成音声より優先して再生されます。

## 効果音のクレジット

使用した音素材：OtoLogic（https://otologic.jp）— [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja)／効果音：[効果音ラボ](https://soundeffect-lab.info)、[ポケットサウンド – https://pocket-se.info/](https://pocket-se.info/)

| 音 | 元素材 | 作者・提供元 |
|---|---|---|
| チャイム `sfx/chime.wav` | Japanese_School_Bell02-03(Slow-Short) | [OtoLogic](https://otologic.jp)（CC BY 4.0） |
| LINE音 `sfx/ringtone.wav` | Smartphone-Ringtone01-01(Dry) | [OtoLogic](https://otologic.jp)（CC BY 4.0） |
| 電話着信音 `sfx/line.wav` | Smartphone-UI_Sound03-02(Dry) | [OtoLogic](https://otologic.jp)（CC BY 4.0） |
| スマホの通知音（ページ内に埋め込み） | 通知音04（最初の1回分） | [ポケットサウンド](https://pocket-se.info/) |
| 扉が開く音（ページ内に埋め込み） | ドアを開ける1 | [効果音ラボ](https://soundeffect-lab.info) |
| 扉が閉まる音（ページ内に埋め込み） | ドアを閉める2 | [効果音ラボ](https://soundeffect-lab.info) |

いずれもアプリでの再生用に加工しています（WAV 変換、無音の調整とフェード、音割れしない範囲での音量調整）。
効果音ラボ・ポケットサウンドの素材は、各サイトの規約・依頼に従い音源ファイルとしては置かず `index.html` 内に埋め込んでいます。各サイトの規約により、取り出しての再配布・再利用はできません。
各素材の出典 URL など詳細は [`sfx/CREDITS.txt`](sfx/CREDITS.txt) を参照してください。

本アプリは各素材の権利者から個別の協力・支持・認証を受けたものではありません。OtoLogic の音源ファイルを再利用・再配布する場合は、クレジット表記を引き継いでください。
