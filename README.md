# 个人导航页

这是一个前后端分离的个人导航页面项目，包含前台导航页面和后台管理系统。

## 项目结构

- `frontend/` - 前端文件
  - `index.html` - 主页面
  - `css/` - 样式文件
  - `js/` - JavaScript文件
  - `admin/` - 管理后台
    - `index.html` - 管理页面
    - `css/` - 管理界面样式
    - `js/` - 管理界面脚本
- `backend/` - 后端API
  - `api/` - API端点
    - `links.php` - 链接管理API
    - `auth.php` - 用户认证API
  - `data/` - 数据存储
    - `links.json` - 链接数据
    - `users.json` - 用户数据

## 功能

### 前台导航页
- 显示导航链接列表
- 按分类筛选链接
- 搜索链接

### 后台管理系统
- 管理员登录认证
- 链接管理（添加、编辑、删除）
- 分类管理

## 使用方法

### 访问前台导航页
1. 将项目文件放置在Web服务器目录下
2. 确保PHP环境已配置
3. 访问 `frontend/index.html` 开始使用

### 访问后台管理系统
1. 访问 `frontend/admin/index.html`
2. 使用默认管理员账号登录：
   - 用户名：admin
   - 密码：admin123
3. 登录后可以进行链接和分类的管理操作