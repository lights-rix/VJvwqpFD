# 前言

欢迎来到本项目的Gitee页面！本项目是一个基于Spring Boot的网上拍卖系统，适用于Java计算机毕业设计。在这里，你将了解到本项目的详细介绍、技术栈、核心代码以及如何获取免费的源码。让我们一起探索这个实战项目吧！

# 内容介绍

本项目是一款功能完善的网上拍卖系统，用户可以在系统中发布拍卖品、参与竞拍、查看拍卖记录等。系统后端采用Spring Boot框架，前端则使用了JS、Vue和CSS3等技术。为了方便开发，我们选择了IDEA或Eclipse作为开发工具，数据库则使用MySQL 5.7或8.0。以下是项目的主要功能模块：

1. 用户模块：注册、登录、修改资料、查看个人竞拍记录等。
2. 商品模块：发布商品、修改商品信息、删除商品、查看商品详情等。
3. 拍卖模块：参与竞拍、查看竞拍记录、取消竞拍等。
4. 管理模块：管理员登录、用户管理、商品管理、拍卖管理等功能。

# 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12、14、16

# 核心代码

以下是本项目中的部分核心代码示例：

```java
// 查询所有拍卖品
@GetMapping("/items")
public List<Item> getAllItems() {
    return itemService.list();
}

// 根据ID查询拍卖品
@GetMapping("/items/{id}")
public Item getItemById(@PathVariable("id") Long id) {
    return itemService.getById(id);
}

// 添加拍卖品
@PostMapping("/items")
public boolean addItem(@RequestBody Item item) {
    return itemService.save(item);
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/336167/33/7381/102378/68bc7787F2f28fea2/5eb246bc6723236c.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/324000/40/16730/17824/68bc7760F3130e662/e3303e0ecbb1913a.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/344857/24/519/36258/68bc7760F78ff407e/1566e120e6cee9e9.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/351418/29/301/26935/68bc7761F8604f95b/86313eb0212b387e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/342934/24/447/20406/68bc7761F41967d5a/7290138cdad2f160.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/327714/15/16993/57977/68bc7762F1cf2fab7/1aac7b1de68aa841.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/336289/33/7677/10055/68bc7762Fc177d764/304caa8db5f44628.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/349681/5/490/15943/68bc7763F7c96723e/5e535ed85759e6e3.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/324324/33/17136/39713/68bc7763F5fa1174d/dbf2899d9520e069.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/329442/26/10322/37542/68bc7764F88e46bab/36802dd462745e6f.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
