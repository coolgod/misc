## 进程
- `ps -ef`: process
  - e: every, 打印所有进程
  - f: full-format，打印所有信息列

## 文件系统
- `chmod 755 path/to/file`：change mode
  - 三组read / write / execute权限
  - 对应文件所属owner, group, others
- `chown foo:bar path/to/file`：change owner
  - `foo:bar`: `foo` is user, `bar` is group
- `df`: disk filesystem
  - `df -h`: human readable
- `du`: disk usage
  - `du -d 1`: depth 1
  - `du -h`: human readable

## 用户
- `su <user_name>`: switch user, 切换登录用户
