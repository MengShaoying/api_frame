# Modify

这个仓库由[api_frame](https://github.com/smarty-kiki/api_frame)修改而成。现在需要实现的功能都处于研究阶段。

## 备注

- 基本功能的controller里面不要写逻辑，逻辑放在Solution内，方便将来移植。
- 生成的文件具体格式需要解耦，防止因为frame框架相关框架发生变更后修改太麻烦。
- 前端实现采用开源的流行的框架。
- Solution内的实现除了兼容frame相关框架之外，尽可能兼容别的框架，增加通用性，也能防止耦合。
