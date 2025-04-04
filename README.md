# Element Simple

一个简单的 Vue 3 组件库，参考 Element UI 的设计。

## 安装

```bash
npm install element-simple
```

## 使用

```javascript
import { createApp } from 'vue'
import ElementSimple from 'element-simple'
import 'element-simple/dist/style.css'

const app = createApp(App)
app.use(ElementSimple)
```

## 组件

### Button 按钮

```vue
<es-button>默认按钮</es-button>
<es-button type="primary">主要按钮</es-button>
<es-button type="success">成功按钮</es-button>
<es-button type="warning">警告按钮</es-button>
<es-button type="danger">危险按钮</es-button>
```

### Input 输入框

```vue
<es-input v-model="value" placeholder="请输入内容"></es-input>
```

### Card 卡片

```vue
<es-card>
  <template #header>卡片标题</template>
  <div>卡片内容</div>
</es-card>
```

## 开发

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 构建
npm run build
``` #   e l e m e n t  
 