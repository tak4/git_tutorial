### ブランチの作成

```bash
git branch feature
```

### リモート追跡ブランチの表示

```bash
git branch -r
```

### 追跡ブランチの更新／削除

```bash
git remote update -p
```

`-p` オプション（または `--prune` オプション）を指定すると、リモートリポジトリで削除されたブランチがローカルリポジトリからも削除

リモートリポジトリの削除

```bash
git push origin --delete feature
```

ローカルリポジトリは削除されないので、別途対応必要

```bash
git branch -d feature
```

リモートリポジトリの追加

```bash
git branch feature
git push -u origin feature
```
