# Comate
## Coding Mate Powered by AI

基于AI的智能代码生成让你的编码更快、更好、更简单！

Comate 由文心大模型 ERNIE-Code 提供技术支持，通过对百度多年积累的非涉密代码数据和 Github 头部公开代码数据进行训练，为您自动生成完整的、且更符合实际研发场景的代码行或整个代码块，帮助每一位开发者轻松完成研发任务。

### 支持能力
- 单行推荐  
  编码过程中稍做停顿，Comate即可按照它的理解，给你补全整行代码.
  
  ![单行推荐](https://baidu-ide.cdn.bcebos.com/comate/images/demo-single-line.gif)

- 多行推荐  
  当待触发推荐的上下文，具备明显的完整逻辑关系（如一个新的方法、函数、判断、循环体等），可自动推荐一个逻辑完整的代码块。
  
  ![多行推荐](https://baidu-ide.cdn.bcebos.com/comate/images/demo-multi-line.gif)

- 多条推荐自由切换  
  如期望查看更多推荐内容，可通过快捷键快速切换，也可打开多条推荐面板，选择最满意的一条并采纳。
  
  ![多条推荐切换](https://baidu-ide.cdn.bcebos.com/comate/images/idea-multi.gif)

### 使用方式
- 选中所推荐代码：Tab
- 切换下一条推荐：alt/option+]
- 切换上一条推荐：alt/option+[
- 关闭当条推荐：Esc
- 查看所有推荐结果：鼠标hover到推荐内容后，显示Comate工具栏，点击 “Comate 补全生成”，在侧边栏中选中采纳

### 支持的语言
已覆盖C、C++、Python、Java、Go、PHP、JavaScript等多个主流语言。
