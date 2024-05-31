# Document-on-the-integration-of-VisualStudio2022-and-GitHub
For NewGraduateTraining - Explanation of how to manage source code using Git and GitHub in VisualStudio 2022
> [!TIP]
> 今後コンソールでlog等を確認する際に日本語が文字化けして何が何だか分からなくならないようにメモ  
> 設定->時刻と言語->言語と地域->管理用の言語設定->システムロケールの変更->ベータ: ワールドワイド言語サポートで Unicode UTF-8を使用にチェック。  
> PCの再起動

<details>

<summary>よく使用するGitコマンド一覧(研修用)</summary>

``` 
git help
``` 
　コマンド一覧を表示
 
```
git コマンド名 --help
``` 
　そのコマンドの使用方法、オプションを詳しくみられる(WEBに遷移する)
 
``` 
git status
``` 
　今編集追加しているファイルを表示

 ``` 
git add ファイル名
``` 
　指定したファイルをステージング
 
 ```
git add -A
``` 
　新規追加、更新、削除のファイルをステージング

 ``` 
git add -u
``` 
　更新、削除のファイルのステージング

``` 
git commit -m "コミットメッセージ入力"
``` 
　コミットする際のコマンド

``` 
git log
``` 
　commit履歴の表示(履歴を見終わったらqで戻れる。

```
git push origin
``` 
　リモートリポジトリにプッシュ 

 </details>

### ~~GitHubにリポジトリが生成できたことを確認できた人はTeamsの個人チャットで報告してくれると嬉しいな。~~
