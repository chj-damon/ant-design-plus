---
order: 2
title: 
  zh-CN: 受控组件
  en-US: Controlled Component
---

## zh-CN

点击按钮切换。

## en-US

Click the button to switch.

```jsx
const Example = () => {
  const rootRef = React.useRef(null);
  const [isFullScreen, setIsFullScreen] = React.useState(false);
  
  return (
    <div 
      style={{ 
        height: 300,
        width: 500,
        backgroundImage: 'url("https://aip.bdstatic.com/portal-pc-node/dist/1568277945052/images/technology/face/detect/demo-card-1.jpg")',
        backgroundRepeat: 'no-repeat',
        backgroundSize: '100% 100%'
      }}
      ref={rootRef}
    >
      <FullScreen 
        status={isFullScreen} 
        targetRef={rootRef}
      />
      <Button 
        onClick={() => { 
          setIsFullScreen(!isFullScreen); 
        }}
      >
        切换
      </Button>
    </div> 
  )
}

render(
  <Example />
)
```
