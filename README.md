# fis3-server-imweb

**fork from https://github.com/fex-team/fis3-server-node**

可以处理上传文件的服务器。

## 设置

```js
fis.set('server.type', 'imweb');
```

## 相关接口

* 使用中间件 `multer` ，可以查询其[文档](https://github.com/expressjs/multer/blob/master/doc/README-zh-cn.md)
* fis 中 mock 数据的相关文档，[这里](http://fis.baidu.com/fis3/docs/node-mock.html)

## 实例

```js
module.exports = (req, res) => {
    //上传的文件在 req.files 中
    // req.files 是一个数组
    const file = req.files && req.files[0];

    // todo
};
```


