## 文件搜索命令 grep

### 格式
- `grep [选项] 字符串 文件名`
- -i 忽略大小写
- -v 排除指定字符串

### find 命令与 grep 命令的区别
- find：在 系统 中搜索符合条件的 文件名，使用 通配符（完全）匹配
- grep：在 文件 当中搜索符合条件的 字符串，使用 正则表达式 （包含）匹配