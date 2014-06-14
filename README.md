# Ngb

> 一个创建和管理golang 项目的工具，具有第三方库的版本控制, 系统需要有ruby的支持

## install

`gem install ngb`

## 使用

1. 在项目目录加入Packagefile，填入类是下面的内容

```
get "labix.org/v2/mgo/bson"
get "github.com/xx/xx"
```

2. 在Packagefile项目所在目录shell 里输入 ngb

