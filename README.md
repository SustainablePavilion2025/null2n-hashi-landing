# null2n-hashi-landing

会場 Wi-Fi（null2n-Guest）への接続案内ページ。GitHub Pages で配信する。

- `index.html` と `404.html` は同じ内容（どのパスで開いても同じ 1 枚を返すため）。
- ページ本体は null2n-audio-relay の `tools/make-wifi-landing.ts` で生成する。ここで直接編集しない。
- 更新するときは生成したファイルで `index.html` と `404.html` の両方を置き換える。
