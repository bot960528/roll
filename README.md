# roll

1. 不采用随机数的方式抽奖；

2. 截止 2019年11月11日12:00:00 所有点赞和评论的人一共是 25 人，按微信 ID 排序(区分大小写)并给与下标为序号；

3. 比赛结束后，如果 fpx 夺冠，则各取双方人头数总和 +1（如打了 3 场，比方分别为：10:10,16:0,14:3；,两方取的值分别为 41「10+16+14+1」和14「10+0+3+1」），再取其乘积（之前的例子里就是 574（41*14））;

4. 将乘积除以总人数取余（之前的例子就是 24「574%25」），所得余数就是获奖者的序号。
