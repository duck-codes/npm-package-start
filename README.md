# npm-package-start

构建`typescript`编写的npm包基础模板，可以在此模板快速开发包。

## 如何使用

```sh
git clone git@github.com:duck-codes/npm-package-start.git
npm i
```

```sh
npm link # 这个命令会在你的文件系统中创建一个符号链接（symbolic link），让你的项目可以像引用一个正常的 npm 包一样，引用你的本地包。
cd ./e2e # 在 e2e 中测试本地包
npm link @ducbbb/npm-package-start # 链接到本地包
```

详细指南：https://duckbb.me/blog/npm-package-start

