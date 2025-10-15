# Flexible Dog In Mountains(山里灵活的狗)
![演示图](./pic/eg.png "eg")

是一个用html,Css,JS编写的web
***
*这是作者在学习6小时前端后编写的web，目的是应付社团作业。*

**在舍友的体验下发现可以当FPS训练器使用** 

操作如下：

用编译器(如vscode)打开 FlexibleDogInMountains.html

1.找到
```
<style>
...
#doge{
    width:***px;
    height:***px;
}
...
<\style>
```
**来修改图片的长和宽**

2.找到
```
<script>
...
function resetTimer(){
  clearTimeout(Timer);
  Timer = setTimeout(() => {
    showTip('山里灵活的狗跑走了！');
    sumFail++;
    fledEl.textContent = `山里灵活的狗共逃脱了：${sumFail} 次`;
    newRound();
  }, ***);
}
...
<\script>
```
***修改`***`为合适的值，初始为1200ms。***
***
背景图来源
@pixiv:Kokonex,pid:106772151
***
特别鸣谢：神人高中同学@宇，祝他复读顺利。他才是山里灵活的狗。





