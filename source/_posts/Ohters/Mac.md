# Mac

## 环境变量

1. profile

   系统环境变量，对所有用户都生效

   ```sh
   /etc/profile
   ```

2. .bash_profile

   用户级别环境变量，对单一用户生效

   ```sh
   ~/.bash_profile
   ```

3. .zshrc

   用户级别环境变量，针对 zsh shell

   ```sh
   ~/.zshrc
   ```

## 光标快捷键

```rust
Ctrl + h 退格删除一个字符，相当于通常的Backspace键
Ctrl + u 删除光标之前到行首的字符
Ctrl + k 删除光标到行尾的字符
Ctrl + a 光标移动到行首（Ahead of line），相当于通常的Home键
Ctrl + e 光标移动到行尾（End of line）
Ctrl + c 取消(cancel)当前行输入的命令，相当于Ctrl + Break

Ctrl + l 清屏，相当于执行clear命令
Ctrl + p 调出命令历史中的前一条（Previous）命令，相当于通常的上箭头
Ctrl + n 调出命令历史中的下一条（Next）命令，相当于通常的上箭头

Ctrl + w 删除从光标位置前到当前所处单词（Word）的开头
Ctrl + y 粘贴最后一次被删除的单词
Ctrl + r 显示：号提示，根据用户输入查找相关历史命令（reverse-i-search）
Option+←          光标单词间移动（向左）
Option+→          光标单词向右移动
```
