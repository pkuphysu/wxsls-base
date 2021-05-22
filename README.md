# 北京大学物院学生会微信的 Serverless 的基本组件

包括 VPC 和数据库. See Also:

- [wxsls-page](https://github.com/pkuphysu/wxsls-page) 零碎网页
- [wxsls-pyfn](https://github.com/pkuphysu/wxsls-pyfn) 回复核心

## 为什么要把这一点点部分单独拿出来呢？

或者换句话说，为什么不放到后端里呢？

因为这部分组件基本不会动。为了避免重复部署和方便管理，就分开放了。

## 为什么不用 MySQL 呢？

太贵了，闲时也须付费。
