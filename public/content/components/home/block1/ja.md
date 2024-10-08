## 主な機能

- 複数のURLに対する一括リダイレクトチェック
- 詳細なリダイレクトパス分析
- HTTPSリダイレクトのサポート
- カスタムユーザーエージェントの選択
- SEO影響評価
- リダイレクトループの検出
- 301と302のリダイレクトの分析
- メタリフレッシュおよびJavaScriptリダイレクトのチェック
- HTTPヘッダーの分析（ステータスコード、X-Robots-Tag、Rel Canonical）

## リダイレクトの理解

### URLリダイレクトとは？

URLリダイレクトは、ユーザーや検索エンジンをあるURLから別のURLに送信する方法です。以下の目的で重要です：

- サイト移行中のSEO維持
- 削除または移動されたページの管理
- ユーザーエクスペリエンスの向上
- 複数のウェブプロパティの統合
- マーケティングキャンペーンの効果追跡

### リダイレクトの種類

- **301リダイレクト（永久的）：** ページが永続的に新しい場所に移動したことを示します。
- **302リダイレクト（一時的）：** ページが一時的に異なるURLにあることを示唆します。
- **メタリフレッシュ：** サーバーレベルではなくHTMLレベルで実装されるリダイレクトの一種です。
- **JavaScriptリダイレクト：** JavaScriptを使用して実装されるリダイレクトで、SEOにはあまり好ましくありません。

## なぜリダイレクトをチェックするのか？

- 適切なSEO実践が行われているか確認する
- サイトを遅くする可能性のあるリダイレクトチェーンを特定して修正する
- ページにアクセスできなくなるリダイレクトループを防ぐ
- 不要なリダイレクトを減らしてサイトのパフォーマンスを最適化する
- サイトの再構築や移行中にリンクエクイティを維持する
- HTTPSリダイレクトが正しく実装されているか確認する
- リダイレクトされたページが正しい宛先を指しているか確認する

## リダイレクトチェッカーの使い方

1. 入力フィールドにURLを入力します（`http://` または `https://` を含めることを忘れないでください）。
2. ドロップダウンメニューからユーザーエージェントを選択します（オプション）。
3. 「リダイレクトをチェック」ボタンをクリックします。
4. ツールがURLを分析するのを待ちます。
5. 詳細な結果を確認します。結果には以下が含まれます：
   - 完全なリダイレクトチェーン
   - 各ステップのHTTPステータスコード
   - リダイレクトプロセス中の中間URL
   - 最終目的URL
   - チェーン内のリダイレクトの総数

## リダイレクトのSEOへの影響

- **301リダイレクト**は、新しいURLにほとんどのリンクエクイティを渡します。
- **302リダイレクト**は、リンクエクイティをあまり渡さないため、SEOにはあまり理想的ではありません。
- リダイレクトチェーンが長すぎると、SEOの価値が希薄になり、ページの読み込み時間が遅くなる可能性があります。
- 重複コンテンツを統合するためにリダイレクトを使用し、サイト全体のSEOを改善します。
- HTTPSリダイレクトを正しく実装して、SEOの価値を失うことなく安全なブラウジングを確保します。
- リダイレクトの定期的な監査を実施し、時間とともに発生する可能性のある問題を修正します。
