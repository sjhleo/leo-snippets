# leo-snippets README

**个人开发自用常用代码片段 VSCode 插件**

## 「 提高效率,早点下班 」

### html

```html
input: "view-design 'i-input' 组件"
date: "view-design 'i-date' 组件"
modal: "view-design 'i-modal' 组件"
dropdown: "view-design 'i-dropdown' 组件"
upload: "view-design 'i-upload' 组件"
table: "view-design 'i-table' 组件"
select: "view-design 'i-select' 组件"
form: "view-design 'i-form' 组件"
page: "view-design 'i-page' 组件"
spin: "view-design 'i-spin' 组件"
poptip:"view-design 'i-poptip' 组件"
checkbox: "view-design 'i-checkbox' 组件" 
radio: "view-design 'i-radio' 组件"
```

    ...待完善

### typescript

mc

```typescript
import { component, Component, config } from "@egova/flagwind-web";
import "./index.scss";
@component({ template: require("./index.html"), components: {} })
export default class MyComponent extends Component {}
```

ms

```typescript
import serviceHandler from "@/decorators/service-handler";
import { CommonService } from "@/services";
export default class MyService extends CommonService {}
```

mf

```typescript
    public MyFunction() {
    // TODO
    }
```

cl

```typescript
console.log();
```

fin

```typescript
for (let item in obj) {
}
```

    ...待完善

### scss

size

```scss
width: 100%;
height: 100%;
```

cflex

```scss
display: flex;
flex-direction: column;
align-items: center;
overflow: hidden;
```

bg-img

```scss
background-image: url();
background-repeat: no-repeat;
background-position: center;
background-size: 100% 100%;
```

ellipsis

```scss
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```

absolute

```scss
position: absolute;
top: ;
left: ;
```

    ...待完善
