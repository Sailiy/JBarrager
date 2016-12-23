# JBarrager
项目地址：http://www.rainx.org/2016/12/22/html5-canvas%E5%AE%9E%E7%8E%B0%E9%AB%98%E5%B9%B6%E5%8F%91%E8%A7%86%E9%A2%91%E5%BC%B9%E5%B9%95%E5%8A%9F%E8%83%BD/

调用方式：
<pre>
html部分代码：
&lt;canvas style="width: 1280px;height: 720px;background-color: rgba(0,0,0,0.2)"&gt;你的浏览器不支持canvas&lt;/canvas&gt;

发送单条弹幕：
$('canvas').barrager([{"msg":"这是我发的。。。哈哈哈"}]);
多条发送方式：
$('canvas').barrager([{"msg":"看着不错。。。。"},{"msg":"哈哈哈。。。。"},{"msg":"不错不错。。"},{"msg":"真好看。。。。"}]);
清除/关闭弹幕：
$('canvas').barrager("clear");

在实际应用，可以通过ajax方式轮询异步获取数据，通过上述语句发送弹幕
如果这个插件帮到了你，希望能给我一个star
</pre>
