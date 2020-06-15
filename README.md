# count
- 元の説明
```
スクリプト構成はタグで囲われた数値を取得して、
数値一桁ごとに＜span＞で囲い、自身の値を取得した後に
その＜span＞タグの中で数値をランダムに表示させるアニメーションを実行させます。
「shuffleAnimation」で設定した時間が経過した後は
＜span＞タグの最後の桁の方からアニメーションをストップさせ、
最初に取得していた元の数値を表示させています。
```

- 変更する点
1. 値がありきで動いているので、なくても動くように変更。
2. 終わるタイミングはクエリを実行して値が返ってきたら終了。
