## 父容器
```css
display: flex;
display: inline-flex; // 行内元素

flex-direction: row | row-reverse | column | column-reverse;
flex-wrap: nowrap | wrap | wrap-reverse;
flex-flow: <flex-direction> || <flex-wrap>;
justify-content: flex-start | flex-end | center | space-between | space-around;
align-items: flex-start | flex-end | center | baseline | stretch;
align-content: flex-start | flex-end | center | space-between | space-around | stretch;
```

## 子容器
```css
order: <integer>;
flex-grow: <number>;
flex-shrink: <number>;
flex-basis: <length> | auto;
flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ];
align-self: auto | flex-start | flex-end | center | baseline | stretch;
```

## 参考文档
- [阮一峰--Flex 布局教程：语法篇](https://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)