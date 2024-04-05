## How To Use

最佳实践：提供一个url的内容如下，然后在radar页面输入url，然后通过iframe内嵌到自己场景应用。

```json
[
  {
    "name": "Composer",
    "ring": "adopt",
    "quadrant": "tools",
    "isNew": "TRUE",
    "description": "Although the idea of dependency management ..."
  },
  {
    "name": "Canary builds",
    "ring": "trial",
    "quadrant": "techniques",
    "isNew": "FALSE",
    "description": "Many projects have external code dependencies ..."
  },
  {
    "name": "Apache Kylin",
    "ring": "assess",
    "quadrant": "platforms",
    "isNew": "TRUE",
    "description": "Apache Kylin is an open source analytics solution ..."
  },
  {
    "name": "JSF",
    "ring": "hold",
    "quadrant": "languages & frameworks",
    "isNew": "FALSE",
    "description": "We continue to see teams run into trouble using JSF ..."
  }
]
```

## 二次开发

- `npm install`
- `npm run dev` - to run application in localhost:8080. This will watch the .js and .css files and rebuild on file changes
- `npm run build:prod`

## 示例

![img](https://raw.githubusercontent.com/boommanpro/my-skill-radar/master/docs-file/front.png)
