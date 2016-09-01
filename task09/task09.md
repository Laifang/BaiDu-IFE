#task09 实现复杂页面
## 任务要求
## 需要注意的问题
   - [ ]发现在其他人的项目中使用了 font-ico 技术 ，参考实现,尤其是 `:before`和`:after`
   - [ ]css spirit 技术实现图片剪切 参考实现
   - [ ]一个任务，实现`<aside></aside>` 的js动态效果，自己满意为止
   - [ ]另一个任务 css实现 `project-nav` 的 `nav-tab` 切换效果 
    
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
      border-top:4px solid blue;
    }   
```

<<<<<<< HEAD
- 第一项目组 project-view 的nav-tab 实现很巧妙，可以完美解决相邻元素上下border融合的问题，可以记下来
=======
- 第一项目组 project-view 的nav-tab 实现很巧妙，通过在wrap内部的div设置负值的`margin-top`,覆盖掉wrap的border,可以完美解决相邻元素上下border融合的问题，可以记下来
       
    

>>>>>>> 5fe9eea9780922fe0d77c8a2764bacbf22ae6557
