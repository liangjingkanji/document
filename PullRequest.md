开源项目伟大在集思广益之处, 个人的思维是狭隘的

## 步骤介绍

这里我们称要修复问题的仓库为: 目标仓库

我们Fork目标仓库后自己账号下会存在一个和目标仓库一样的仓库我们称为: Fork仓库



1. Fork指定的目标仓库
2. 克隆自己Fork的交叉仓库
3. 修改代码并提交Push到自己刚才Fork仓库
4. 然后打开目标仓库地址会出现一个PullRequest请求按钮
5. 点击按钮填写信息即可等待仓库Owner审核并合并代码



这种共同修复一个仓库的行为称为创建PR

## 截图步骤

Fork仓库

![image-20210426215018269](https://i.imgur.com/S5nhyma.png)



然后在你自己的账号下就拥有一个一模一样的仓库

![image-20210426215456908](https://i.imgur.com/8CbAFpm.png)



克隆自己的仓库然后修改代码并且提交和Push上来, 然后打开GitHub Fork仓库页会发现两个按钮. 点击`Pull request`发起请求(Compare可以自己预览自己有哪些修改变动)

1. 在创建Pull request前我们应该保证我们已经拉取到目标仓库最新代码

![image-20210426221350452](https://i.imgur.com/hStSSZ2.png)



然后会进入一个创建Pull request页面

1. 检查并确定合并的分支无误
2. 点击 `Pull reuquest` 绿色按钮

![image-20210426221720734](https://i.imgur.com/tyipHe2.png)



描述你的Pull request 然后点绿色按钮提交

![image-20210426221957729](https://i.imgur.com/f1DZLxD.png)



最终等待作者审查代码并合并或者和作者互喷

![image-20210426222441374](https://i.imgur.com/7TwZP7Z.png)



1. 这时如果你觉得还有新的提交内容可以继续修改并Push你的Fork仓库会更新此Pr
2. 如果觉得你的修改有问题可以选择`Close pull request`关闭此Pr



以上演示我们是基于直接在问题存在的master分支修改. 实际上我们可以选择创建新的分支. 便于和目标仓库最新代码合并然后再创建PR



## 修改文档

同样先Fork仓库



然后我们打开需要修改的文档页面点击铅笔✏️图标

![image-20210426223445017](https://i.imgur.com/FSvPmpY.png)



然后编辑文档内容(文档为Markdown语法编写)

![image-20210426223550117](https://i.imgur.com/ucfX0iq.png)



编辑完成确认, 描述修改内容, 然后点击`Propose changes`

<img src="https://i.imgur.com/UJ40tOU.png" alt="image-20210426223627630" style="zoom:50%;" />

然后就是`Create Pull request`

![image-20210426223810922](https://i.imgur.com/OLfBk7y.png)
