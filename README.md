# picsgo
批量上传图片到七牛
# 用法
## Step 1
配置config.json

key | explain |
--- | --- |
rs | 七牛域名 |
ak | 七牛AccessKey |
sk | 七牛SecretKey |
name | 账户名(随意取) |

## Step 2
进入picsgo目录为picsgo创建软连接

```
ln -n picsgo /usr/local/bin/picsgo
```

# Step 3
上传图片

```
picsgo if-pbl 2015/01/18 /Users/jemy/Documents/qiniu.jpg
```

- if-pbl:七牛空间名
- 2015/01/18:文件前缀
- /Users/jemy/Documents/qiniu.jpg:图片

第三个参数可以是图片也可以是目录