# 基于Matery主题修改

> 一个基于材料设计和响应式设计而成的全面、美观的Hexo主题，本主题是在原作者主题的基础上进行自定义修改，原作者地址：<https://github.com/blinkfox/hexo-theme-matery>

# Hexo常用命令

> Hexo官方文档：https://hexo.io/docs/  ；https://github.com/hexojs/hexo

## 使用方法

1. 克隆仓库源码

   ```bash
   git clone https://github.com/wuye88/hexo-theme-matery.git
   ```

2. 安装hexo

   方法一：全局安装，省事，新手推荐！！！

   ```
   npm install -g hexo-cli
   ```

   方法二：局部安装：

   ```
   npm install hexo
   
   # 使用：npx hexo <command>
   
   # 对于linux用户，执行下列命令添加环境变量后可以直接使用:hexo <command>
   echo 'PATH="$PATH:./node_modules/.bin"' >> ~/.profile
   ```

3. 安装必要依赖环境

   ```bash
   npm install
   ```

   环境安装完毕后即可进行预览

4. 删除.git文件夹，修改`_config.yml`文件的一些配置

### 环境安装

```bash
# node version >= v12.0
npm install
```

### 启动本地预览

```bash
hexo s
```

### 生成静态文件

```bash
hexo g
```

### 清楚缓存

```bash
hexo clean
```
