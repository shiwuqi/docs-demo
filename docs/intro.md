<!--
 * @Author: shiqi shiqi@indexed.cn
 * @Date: 2022-06-09 11:26:32
 * @LastEditors: shiqi shiqi@indexed.cn
 * @LastEditTime: 2022-06-09 16:50:49
 * @FilePath: /docs-demo/docs/intro.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# Hello Docs
export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '2px',
      color: '#fff',
      padding: '0.2rem',
    }}>
    {children}
  </span>
);

<Highlight color="#25c2a0">Hello World</Highlight>

```jsx
export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '2px',
      color: '#fff',
      padding: '0.2rem',
    }}>
    {children}
  </span>
);
```