## 成果物の比較と依存関係のキャッシング

成果物とキャッシングは、{% data variables.product.prodname_dotcom %}にファイルを保存できるようにするので似ていますが、それぞれの機能のユースケースは異なっており、入れ替えて使うことはできません。

- パッケージ管理システムからのビルドに依存関係など、ジョブやワークフローの実行間で、頻繁に変更されることがないファイルを再利用したい場合にはキャッシュを使ってください。
- ビルドされたバイナリやビルドログなど、ジョブが生成するファイルを保存して、ワークフローの実行が完了したあとに見たい場合には、成果物を使ってください。 
