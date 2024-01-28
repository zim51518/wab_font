<h2>引入字体</h2>
<code >
@font-face { 
  font-family: 'web_woff_weizhi';          <span>#字体代号（用于引用）</span>
  src: url('字体连接') format('woff');      <span>#字体连接和字体类型</span>
  font-weight: 600;                        <span>#字体大小</span>
  font-style: normal;                      <span>#字体样式</span>
}
</code>
<h2>应用字体标签</h2>
<code >
body, button, select, input, textarea{
    font-family: 'web_woff_weizhi';
    font-weight: 500;
}
</code>
