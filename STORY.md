# Day073 Story — Market Bag Balancer

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day073専用にテーマをseed固定して再生成時の見た目を安定化
- utility用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: market_bag_balance
- Mechanic: sort_baskets
- Input/Output: basket_items -> load_split
- Audience Promise: レジ台で詰め直す回数を減らせる。
- Publish Hook: 買った物の重さと壊れやすさを入れると、袋ごとの重さ差と避ける組み合わせが見える。
- Complexity Tier: small
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day073｜買い物袋かたより直し
買い物袋の重さ偏りを直すツールです。
