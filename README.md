# okacslab20181117
20181117 AzureML勉強会 in Okayama用

データ取得元はこちら(http://www2.informatik.uni-freiburg.de/~cziegler/BX/)

CSV Dumpをダウンロードすると、カンマ区切りでなくセミコロン区切りのデータになっていた(カンマを含むデータが含まれている為と思われる)ので、Azure Machine Learning Studioにすんなりアップロードできるように、タブ区切りテキスト(tsv)ファイルに変換したものを配置しています。
zipファイルを解凍すると以下の3ファイルが展開されます。
 - BX-Book-Ratings.tsv
 - BX-Books.tsv
 - BX-Users.tsv

以下のページを参考に3ファイルともAzure Machine Learning Studio上にアップロードしてください。
https://docs.microsoft.com/ja-jp/azure/machine-learning/studio/import-data-from-local-file
