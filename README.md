# NJU-judge-teaching
每学期一次的评教真是扯蛋，那么多框框谁点的过来

作为计算机的学生，肯定要自动化啦！！！

## 功能
### 本科生
- 所有选项自动选择“很好”，文本评价留空
- 自动进入下一位教师的评价（以及下下位，反正所有都会评好）
- 自动跳过“我最喜爱的教师”和助教评价

### 研究生
- 所有选项自动选择“符合”，文本评价留空
- 确认分数为"100"，并提交
- 轮询评教页面未评教课程
- 控制台打印当前进展

## 食用方式
### 本科生
1. 进入评教网页。在[南京大学办事大厅](https://ehall.nju.edu.cn/ywtb-portal/official/index.html)登陆后搜“本-网上评教“即可。
2. 点一下`待我评教`，进入这个页面
<img width=50% alt="image" src="https://github.com/SuperKenVery/NJU-judge-teaching/assets/39673849/6f0f0726-3074-4287-b1e9-b42a6469665d">

3. 打开浏览器的开发者工具（F12），打开Console（控制台）页面。有的浏览器（比如苹果Safari或者Microsoft Edge）默认状态下会屏蔽开发者工具，按了F12也不出来，这种情况可以自己搜一下怎么办。
<img width="1329" alt="image" src="https://github.com/SuperKenVery/NJU-judge-teaching/assets/39673849/41603738-5726-48c2-9ce6-a870d1635e11">
    
4. 把`judge.js`的内容全都复制进来，粘进console里，回车（Enter）。注：首次粘贴需要先打字输入`允许粘贴`或者`Allow paste`
5. 看网页自己评完吧～
6. 在助教评教页面再来一次（
   - 如果是chromium系浏览器（edge，chrome等），不能再次粘贴，要在Console里输入`await main()`
   - 如果是Firefox则需要再次粘贴

### 研究生
1. 进入评教网页。在[南京大学办事大厅](https://ehall.nju.edu.cn/ywtb-portal/official/index.html)登陆后搜“网上评教“即可。
2. 进以下界面：![image](https://github.com/user-attachments/assets/72c07021-3e04-4811-ac9d-fba95ac3d4df)
3. 打开浏览器的开发者工具（F12），打开Console（控制台）页面。
4. 把`Judge_Graduate.js`的内容全都复制进来，粘进console里，回车（Enter）。注：首次粘贴需要先打字输入`允许粘贴`或者`Allow paste`
5. 脚本自动评教，Console 中打印当前进展
![7fd721f7a399d6f1e1d28befef322879](https://github.com/user-attachments/assets/15222d37-71e6-43ea-8020-ebc3c3712972)

