# Lodash
 [Lodash]:是一个一致性、模块化、高性能的 JavaScript 实用工具库(https://www.lodashjs.com/)

# 解决nginx部署vue刷新404问题：
 try_files $uri $uri/ /index.html;
  ```
  server {
        listen       1004;
        server_name  localhost;
        location / {
            root  C:\Users\Administrator\Desktop\xlc\speech-management/lk_manage;
            index index.html index.htm;
            try_files $uri $uri/ /index.html;
        }
    }
    ```

# vue ant 汉化：
  ```
     declare module 'ant-design-vue/lib/locale-provider/zh_CN' {
  const zhCN: any;
  export default zhCN;

}
   ```