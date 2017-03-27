# 非官方《SITCON Workshop - Git 版本控制入門》學習資料
## License
PD, with exception of resource used under fair use principle

## 版本控制系統簡介
### 問題與解決方案

### 分類
#### 本地

#### 集中式

#### 分散式

## 事前準備

## 環境設定
* git log
	* 版號
	* 作者資訊
	* 

````
git config --global user.email "you@example.com"

git config --global user.name "Your Name"

git config --global color.ui true

git config --global core.editor vim

git config --global alias.co commit

# 方便了解樹狀圖的命令別名
git config --global alias.lg "log --color --graph --all --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --"

```
