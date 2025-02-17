---
title: Entity (エンティティ)
slug: Glossary/Entity
tags:
  - CodingScripting
  - Composing
  - Glossary
  - HTML
translation_of: Glossary/Entity
---
{{glossary("HTML")}} **エンティティ**とは、アンパサンド (`&`) で始まりセミコロン (`;`)で終わるテキスト (文字列) のひと固まりです。エンティティは（通常は HTML コードとして解釈される）予約済み文字や、(ノーブレークスペースのように) 見えない文字を表示するためによく使用されます。標準キーボードでは入力が難しい文字の代わりに使用することもできます。

> **Note:** 多くの文字は覚えやすいエンティティです。例えば、コピーライト記号 (`©`) のエンティティは `&copy;` です。覚えにくものとしては、`&#8212;` や `&#x2014;` があります。[リファレンス表](https://html.spec.whatwg.org/multipage/named-characters.html#named-character-references)や[デコーダーツール](https://mothereff.in/html-entities)を使用してみてください。

## 予約済み文字

HTML で使用されるために予約されている特別な文字があり、ブラウザーはそれら予約済み文字を HTML コードとしてパースします。例えば、小なり (`<`) 記号を使用すると、ブラウザーは文章を{{Glossary('Tag','タグ')}}として解釈します。

これらの文字をテキストとして表示するためには、以下のテーブルで示されている、対応する文字エンティティに置き換えてください。

| 文字 | エンティティ | 注記                                                                             |
| ---- | ------------ | -------------------------------------------------------------------------------- |
| &    | `&amp;`      | エンティティや文字参照の開始として解釈されます。                                 |
| <    | `&lt;`       | {{Glossary('Tag','タグ')}}の開始として解釈されます。                   |
| >    | `&gt;`       | {{Glossary('Tag','タグ')}}の終了として解釈されます。                   |
| "    | `&quot;`     | {{Glossary('Attribute','属性')}}の値の開始や終了として解釈されます。 |

## 関連情報

### 技術リファレンス

- [文字エンティティの公式リスト](https://html.spec.whatwg.org/multipage/named-characters.html#named-character-references)
