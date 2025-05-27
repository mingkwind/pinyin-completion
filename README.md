本项目基于[adaptee/pinyin-completion](https://github.com/adaptee/pinyin-completion)进行修改，因为这个项目太老了，很多方法都是python2的，python3安装会报错，因此进行更新

安装方法：

```zsh
git clone https://github.com/mingkwind/pinyin-completion.git  ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/pinyin-completio
cd ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/pinyin-completio
pip3 install . --user
```

之后在zsh加入

```zsh
source ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/pinyin-completion/shell/pinyin-comp.zsh
```

重新打开zsh或者`source ~/.zshrc`即可使用拼音首字母补全
