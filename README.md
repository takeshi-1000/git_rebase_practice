1. https://github.com/takeshi-1000/git_rebase_practice 作成
2. Main ブランチpush
3. Localで、feature/1 ブランチ作成し、チェックアウト
4. Feature/feature.html 作成
5. githubのwebサイト上から、main/main.htmlファイルを作成
6. feature/1 状態だと思うので、git rebase main をする
7. Current branch feature/feature1 is up to date. と出る
8. Git fetch origin main し git rebase main しても、Current branch feature/feature1 is up to date. と出る
9. Main にチェックアウト
10. Remoteの変更を取り込む(git pull origin main)
11. Feature/feature1にチェックアウト
12. git rebase main すると、 Successfully rebased and updated refs/heads/feature/feature1.
