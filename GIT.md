## Working Directory
- `git clean -xfd`
  - `x`: 
  - `f`: force
  - `d`: delete, remove untracked directories in addition to untracked files
- `git checkout`：从本地index取
  - `-b` 创建新branch
- `git pull`：从remote取

## Stage
- `git add .`
- `git status`
- `git diff`：比较working directory和staging area
  - `--name-only`：只显示文件名
  - `--cached` 比较staging area和HEAD之间的diff

## Commit
- `git commit -m 'commit comment' [--allow-empty]`
- `git reset --hard commit_hash`
- `git log`
  - `--graph`

## Tagging
- `git tag`
  - `sort:version:refname`：将`refname`当做版本号进行排序
  - `--list 'pattern*'`：根据带wildcard的pattern进行filter

## Remote
- `git push orgin branchName`：
  - `-u` / `--set-upstream`：为当前branch设置upstream
  - `--force`：强制push，覆盖remote冲突的commit
- `git remote`
  - `-v`: verbose


