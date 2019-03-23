[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)




#步骤
## 对文件做出修改后完成正常commit操作 1、git add .  2、 输入git cz，根据提示完成信息输入生成commit msg；在发布版本之间可以执行任意次commit 
## 发布版本 以生成一个小版本为例，敲入指令(npm run release -- --release-as minor)，即生成了一个最新的小版本 此时在CHANGELOG.md文件会生成一个最新的版本的log链接
## 根据版本生成之后的提示输入 git push --follow-tags origin master 提交到远程分支；
## 推送到远程仓库之后，根据生成的链接就可以看到这个版本期间的所有CHANGELOG了