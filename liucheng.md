*  初步搭建 - https://juejin.cn/post/6947872709208457253
   1. 初始化
      npm init -y
   2. 添加 ts
      ① npm add typescript   --dev
        npm install --save typescript 
      ② 创建 tsconfig.json 文件 
        x - tsc --init (这样是局部安装，会导致不能在控制台或者终端使用)
        解决方案：
        - 全局安装 typescript - npm install -g typescript
        - 使用 node下npx - npx tsx --init 创建 tsconfig.json 文件
      ③ 增加相关配置
      ④ 卸载
       - npm uninstall typescript @types/node @types/react @types/react-dom @types/jest
       - 删除配置文件

   3. 添加 EsLint - 代码规范检查
     - 添加脚本

   4. Prettier - 代码格式化
        **npm install prettier --save --dev**
     - 添加脚本
   5. EditorConfig - 统一代码风格
     - 安装插件
     - 创建 .editorconfig 文件
   6. StyleLint - 代码风格检查
     - 安装
       - npm add stylelint stylelint-config-standard --dev
     - 创建 stylelintrc.js 文件
     - 配置脚本
       - //  自动修复src 目录下的所有 Less 文件不规范的内容 
       - "lint:style": "stylelint --fix \"src/**/*.less\" --syntax less"

   7. 集成的开源工具（该项目中未使用，slt应该使用的该工具） - @umijs/fabric
     - 安装

   8. 

  
