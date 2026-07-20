# 内科 新着論文ダッシュボード

世界の一流総合医学誌から、過去12か月の新着論文を日本語要約付きでまとめた静的Webサイトです。GitHub Pages で公開しています。

## 収録ダッシュボード

| 雑誌 | 説明 | ページ |
|---|---|---|
| **NEJM** (New England Journal of Medicine) | 臨床医学で最も影響力の大きい総合誌 | [`/nejm/`](./nejm/) |
| **The Lancet** | 世界的権威を持つ英国の総合医学誌 | [`/lancet/`](./lancet/) |

## 構成

```
.
├── index.html        トップページ（各ダッシュボードへのリンク）
├── nejm/index.html   NEJM ダッシュボード（単一HTML・自己完結）
└── lancet/index.html Lancet ダッシュボード（単一HTML・自己完結）
```

- 各ページは HTML + CSS + JavaScript を1ファイルに内包した自己完結型。
- レスポンシブ対応（スマートフォン表示に最適化）。
- データ出典: PubMed (NCBI E-utilities)。

## 注意

各論文の要約は原著抄録に基づく日本語訳です。臨床判断の際は必ず原著をご確認ください。
