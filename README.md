# 英語発表の音声練習

英語原稿を聞きながら声に出し、録音で振り返るための練習用ツールです。

公開URL: https://b221393.github.io/english-speech-practice/

- 全24ページ、143文の英文と日本語を表示します。
- 「原稿を再生」または各文の「再生」をタップして聞きます。速度調整・繰り返しにも対応します。本編14ページ、参考10ページです。19〜24は仕様補足です。
- 難語・頻出語33語をクリックすると読み上げます。
- 対応ブラウザでは録音・音声保存・任意の英語文字起こし・練習記録CSVを利用できます。

音声は端末の読み上げ機能を使います。スマホの音量を上げ、再生ボタンをタップしてください。英語の声は端末により異なります。ページを開いただけでは自動再生しません。

録音はページ内に保持されます。必要な音声は画面を閉じる前に保存してください。アプリ独自の録音アップロード先・解析サーバー・アクセス解析はありません。任意の文字起こしを有効にすると、ブラウザの認識サービスへ音声が送られる場合があります。語の一致率は発音の点数ではありません。

ブラウザの対応状況やマイク権限により、録音・文字起こしを利用できない場合があります。原稿と単語の再生は録音を有効にせず使えます。

## 公開方法

`main` ブランチのルートをGitHub Pagesの公開元にしています。`index.html` の更新をプッシュすると再公開されます。ビルドや外部JavaScriptライブラリは不要です。

## 仕様資料

- [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [MDN SpeechSynthesis](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis)
- [MDN SpeechRecognition](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition)
