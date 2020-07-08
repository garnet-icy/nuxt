## nuxt
1.安装
+ npm install -S nuxt 项目中安装nuxt
+ npx create-nuxt-app <项目名> (自定义项目名)
+ 选择要下载的各个框架
+ 项目中的page页新建index.vue文件
+ npm run dev
+ **首页默认路由使用asyncData会报错，找不到数据，应使用data**

2.路由的配置
+ page文件下新建文件夹与vue文件，自动生成路由
+ 动态路由：
  ```
  文件名带前缀_，自动识别为动态路由,当同级别文件夹下含有index.vue时，无动态路由时会指向index路由。
  ```
+ 嵌套路由：
  ```
  主目录下有parent.vue作为父组件，同级目录下有同名文件夹存放子组件，其中index.vue为默认显示组件
  在parent.vue中写入nuxt-child标签，使用nuxt-link跳转
  ```

3.页面布局
+ layouts文件夹为布局文件夹，可设置多种布局格式，可设置公共头部尾部
+ 其他页引入
  ```
  layout:'default'
  ```