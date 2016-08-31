#task09 实现复杂页面
## 任务要求
## 尚存在的问题
   - 
    
## 已经解决的问题
   - 

## 需要记下的知识:
- `box-sizing` 属性 是内容盒模型 盒子大小等于设置大小，`padding`和`border`被包含在定义的`width`和`height`之内；
    
```css
    - [tips]:用于解决hover状态文字位置改变的问题

    div {
    box-sizing: border-box;
    border-top:4px solid #fff;
    background-color: #fff; /* 注意 一开始border与back颜色相同，但是要注意居中问题*/
    }
      div:hover {
    border-top:4px solid #blue;
    }   
```
       
    