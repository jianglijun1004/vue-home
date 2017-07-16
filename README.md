## vue-home

>技术点 

用vue社区提供的API，基于vue+vue-cli+vue-router+axios+webpack开发的vue社区

UI用Muse-UI

css用scss，flex布局，rem做移动端适配，最终效果web端移动端都适配。

用localStorage做缓存


> 建议先去社区[注册](https://www.vue-js.com/signup)拿accesstoken登录体验(注册可以直接用github账号，挺快的)

[demo](http://www.hxvin.me/vue-home/dist/)

[点击查看gif动图展示](http://ooytyiziz.bkt.clouddn.com/vue-home.gif)

[项目API](https://www.vue-js.com/api/)
### 手机扫描查看效果
![手机扫描查看效果](https://github.com/Hxvin/vue-home/blob/master/src/assets/1495982696.png)

> 完成功能

- [x] 首页列表
- [x] 下拉加载
- [x] 用户信息（点击头像）
- [x] 主题内容
- [x] 登录功能
- [x] 收藏（取消收藏）主题
- [x] 评论列表
- [x] 点赞（取消点赞）功能
- [x] 消息中心（已读、未读）
- [x] 个人中心
- [x] 发表评论
- [x] 回复评论
- [x] 发布主题（支持markdown编辑且可预览）
- [ ] vuex重构

### 安装运行

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
* 注意`npm run dev` 之后 默认浏览器打开的是http://localhost:8080  请换成http://localhost:8080/vue-home/dist

等写完项目后 打包上线
* $ npm run build

>注意：npm run dev 之后 默认浏览器打开的是http://localhost:8080  请换成http://localhost:8080/vue-home/dist

```
```
