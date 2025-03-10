---
title: FullScreen
type: Basic Components
subtitle: Full Screen
order: 3
---

## API

### FullScreen

| Property  | Description             | Type                | Required | Default | Alternative |
| --------- | ----------------------- | ------------------- | -------- | ------- | ----------- |
| className | 额外类名                | string              | 否       | --      | --          |
| style     | 额外样式                | React.CSSProperties | 否       | --      | --          |
| status    | 是否全屏(受控属性)      | boolean             | 否       | --      | --          |
| isBody    | 是否是整个页面          | boolean             | 否       | `false` | --          |
| targetRef | 需要控制全屏的元素的ref | RefObject<Element>  | 否       | --      | --          |
| onChange  | 全屏状态改变的回调      | function            | 否       | --      | --          |
