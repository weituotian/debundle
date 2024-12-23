## 运行
```
-i ../tests/eqxiu/view-d8cf666.min.js -o dist/ -c ../tests/eqxiu/debundle.config.json
```

## 文档
- AST 抽象语法树学习
- https://blog.csdn.net/Dear_Mr/article/details/72587908
- jstillery
- https://mindedsecurity.github.io/jstillery/

## todo 
- 解决某些js代码空问题
- !0， !1 替换 [X]
- comma表达式替换 [X]
- 三目运算符替换 [X]
- 变量定义替换 [X]

用于测试的js代码:
```
function ss(module) {
    var exports = this;
    if (module.preventDefault(), module.stopPropagation(), this.startStatus) {
        for (var require = this.getRoute(module), i = require.x, o = require.y, r = this.circleRadius(i, o, this.lastX, this.lastY); r > this.step;) this.lastX += (i - this.lastX) / r * this.step, this.lastY += (o - this.lastY) / r * this.step, this.drawCircle(this.lastX, this.lastY), r = this.circleRadius(i, o, this.lastX, this.lastY);
        if (this.drawCircle(i, o), this.lastX = i, this.lastY = o, this.percent() > this.per) {
            this.clear(), this.startStatus = !1, this.$canvas.hide(), this.thisTimeHasEnd = !0, h.showMaskPanel(this.$mask, this.eqxPage);
            var a = this.isWinner ? this.$winLotteryHtml : this.$lostLotteryHtml;
            setTimeout(function() {
                var module = exports.eqxScene.bgm;
                module && module.hide(), exports.$canvas.show(), a.show();
            }, 500);
        }
    }
}
```
