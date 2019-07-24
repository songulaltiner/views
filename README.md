# Views

预览地址：http://uidoc.ngrok.apicloud-system.com/views.html
> Views是APICloud提供的一套轻量的CSS基础样式库，专注于解决移动端APP以及H5开发体验和视觉的统一。Views项目本身使用sass开发和管理，使用之前，需要编译为发布版的CSS以及JS。

---

## 编译Release版本的Views

如果您想自己构建Views，请遵循以下步骤。

使用[npm](http://www.npmjs.com)安装[Grunt](http://gruntjs.com) 编译工具:

```bash
npm install -g grunt-cli
```

进入[Views](https://github.com/eclipsesource/tabris-js) 源码根目录并获取安装依赖项，然后生成:

```bash
npm install
grunt
```
/dist/目录下即为编译好的Views。

## License

MIT © [APICloud](https://www.apicloud.com)
