<html lang="en"><head>
    <meta charset="UTF-8">
    <title></title>
<style id="system" type="text/css">h1,h2,h3,h4,h5,h6,p,blockquote {    margin: 0;    padding: 0;}body {    font-family: "Helvetica Neue", Helvetica, "Hiragino Sans GB", Arial, sans-serif;    font-size: 13px;    line-height: 18px;    color: #737373;    margin: 10px 13px 10px 13px;}a {    color: #0069d6;}a:hover {    color: #0050a3;    text-decoration: none;}a img {    border: none;}p {    margin-bottom: 9px;}h1,h2,h3,h4,h5,h6 {    color: #404040;    line-height: 36px;}h1 {    margin-bottom: 18px;    font-size: 30px;}h2 {    font-size: 24px;}h3 {    font-size: 18px;}h4 {    font-size: 16px;}h5 {    font-size: 14px;}h6 {    font-size: 13px;}hr {    margin: 0 0 19px;    border: 0;    border-bottom: 1px solid #ccc;}blockquote {    padding: 13px 13px 21px 15px;    margin-bottom: 18px;    font-family:georgia,serif;    font-style: italic;}blockquote:before {    content:"C";    font-size:40px;    margin-left:-10px;    font-family:georgia,serif;    color:#eee;}blockquote p {    font-size: 14px;    font-weight: 300;    line-height: 18px;    margin-bottom: 0;    font-style: italic;}code, pre {    font-family: Monaco, Andale Mono, Courier New, monospace;}code {    background-color: #fee9cc;    color: rgba(0, 0, 0, 0.75);    padding: 1px 3px;    font-size: 12px;    -webkit-border-radius: 3px;    -moz-border-radius: 3px;    border-radius: 3px;}pre {    display: block;    padding: 14px;    margin: 0 0 18px;    line-height: 16px;    font-size: 11px;    border: 1px solid #d9d9d9;    white-space: pre-wrap;    word-wrap: break-word;}pre code {    background-color: #fff;    color:#737373;    font-size: 11px;    padding: 0;}@media screen and (min-width: 768px) {    body {        width: 748px;        margin:10px auto;    }}</style><style id="custom" type="text/css"></style></head>
<body marginheight="0"><h2>DOL是什么?</h2>
<p>DOL(The distributed operation layer)是一个可以运行编译并行式程序的软件开发框架。

</p>
<h2>DOL由什么组成？</h2>
<ul>
<li>DOL应用程序编程接口：DOL定义了一系列的计算通信规则，使其可以对SHAPE平台上的分布式并行应用程序进行编程。使用这些规则，程序员无需了解底层架构的详细知识就可以编写程序。</li>
<li>DOL功能仿真：程序员可以在上面测试程序的正确性、调整参数。</li>
<li>DOL映射优化：用于计算应用程序到SHAPE架构平台上的最优映射。</li>
</ul>
<h2>DOL安装笔记</h2>
<ol>
<li>虚拟机安装Ubuntu</li>
<li>安装必要环境</li>
<li>下载dol文件压缩包和systemc文件压缩包，拖入Ubuntu中。</li>
<li>解压压缩包</li>
<li>编译systemc</li>
<li>设置参数
<img src="图片1.png" alt="configure"></li>
<li>修改路径 home/amy/systemc-2.3.1 <em>这里的路错误会影响到之后的build步骤</em></li>
<li>编译DOL，运行第一个例子</li>
</ol>
<h2>实验感想</h2>
<p>这次实验主要是配置实验环境，总体来说就是按照PPT上来做，但是我在修改路径时打多了一层文件夹，导致后面build的时候失败了。
Edit By <a href="http://mahua.jser.me">MaHua</a></p>
</body></html>