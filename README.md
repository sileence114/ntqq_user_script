# ntqq_user_script
NTQQ 相关用户自定义脚本
- [LiteLoaderQQNT](https://github.com/LiteLoaderQQNT/LiteLoaderQQNT) 可以在 NTQQ 上加载插件
  - [LiteLoaderQQNT-CanCanNeed](https://github.com/MapleRecall/LiteLoaderQQNT-CCND/tree/main) 通过内容替换保护隐私，不影响布局和样式
  - [Transitio](https://github.com/PRO-2684/transitio) 用于加载 CSS 片段
  - [Scriptio](https://github.com/PRO-2684/Scriptio) 用于加载渲染层的 JavaScript 片段


## user css
### [admin-s-green-hat](https://raw.githubusercontent.com/sileence114/ntqq_user_script/refs/heads/main/css/admin-s-green-hat.css)
| 浅色模式 | 深色模式 |
| --- | --- |
| ![b6ab7d2a3bcc1dc8516639d2e46cd098](https://github.com/user-attachments/assets/5d387de6-6c7a-405f-a1af-70d0f39e1c81) | ![c8d162630b23e6fe11fb8a6e0a5b9eb6](https://github.com/user-attachments/assets/9552b6ac-57fc-4a9d-b184-0407e981fa7d) |
> 让管理员戴回绿帽（将管理员头衔颜色重新改为绿色）
- 如果不喜欢我调的颜色，你可以在设置中自己调整
- 支持深色模式

### [less-spacing](https://raw.githubusercontent.com/sileence114/ntqq_user_script/refs/heads/main/css/less-spacing.css)
| 未启用 | 启用后 |
| --- | --- |
![image](https://github.com/user-attachments/assets/c3cd0853-1c7a-417d-9bd9-7dafe040542e) | ![image](https://github.com/user-attachments/assets/579b5136-e40e-4151-a911-d808604f1a4a)
> 减少元素间距
> （后续优化方向）尽量减少列表项的间距，让窗口显示更多内容。
- 已调整：
  - 消息列表
  - 转发的聊天记录
  - 聊天区域
- 画饼：
  - 适配轻量工具箱的合并消息模式
  - 聊天记录窗口
- 有点麻烦？（PR Please!）
  - 群聊窗口边栏成员列表（虚拟滚动区域列表元素数量有限，会露出空白的列表元素）
  - 其他犄角旮旯的地方
