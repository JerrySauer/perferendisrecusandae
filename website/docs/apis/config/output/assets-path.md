---
sidebar_label: assetsPath
---

# output.assetsPath

:::info 适用的工程方案
* 模块
:::

* 类型： `string`
* 默认值： `styles`


指定资源产物目录路径。

例如，可将资源产物输出目录改成 `assets-styles` 目录：

```js title="modern.config.js"
import { defineConfig } from '@modern-js/module-tools';

export default defineConfig({
  output: {
    assetsPath: 'assets-styles',
  },
});
```
