# vue项目中使用富文本编辑器

本文介绍在vue项目中如何使用富文本编辑器，以`vue2-editor`为例。

1. 在项目中安装`vue2-editor`， 使用命令：

   ```vue
   npm install --save vue2-editor
   ```

2. 在需要使用的页面vue文件中引入

   ```vue
   import { VueEditor } from 'vue2-editor'
   ```

3. 注册组件

    ```vue
    components: {
    	VueEditor 
    }
    ```

4. 使用组件即可

    ```vue
    <vue-editor v-model="content"></vue-editor>
    ```

    

