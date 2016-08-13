## fis-iconfont-demo

---

### 生成字体

> 命令行方式调用  
```
fis3 iconfont -n wiifont -s ./src/resource/svgs -d ./output
```

> 命令行方式可以复写 fis-conf.js 的配置，如果不加任何参数，则完全读取 fis-conf.js 的配置  
```
fis3 iconfont
```

> fis-conf.js 配置
```javascript
fis.config.set("iconfont", {
    'src': '/src/resource/svgs', //图标目录
    'dest': '/src/resource/fonts', //产出字体目录
    'fontname': 'wiifont', //产出字体名称
    'order': 'name' //name或者time //图标按名称还是按修改时间排序，默认按名称排序
});
```



