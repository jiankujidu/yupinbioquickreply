# 优品生物快回复 Android应用

## 功能列表

### 核心功能
1. **悬浮窗功能**
   - 悬浮窗权限申请
   - 悬浮窗UI界面
   - 话术快速选择面板
   - 全局快捷键绑定

2. **话术管理系统**
   - 三级分类：公司话术、小组话术、私人话术
   - 多彩分类和标签系统
   - 话术编辑、删除、批量管理
   - 关键词模糊搜索

3. **快捷回复**
   - 一键点击发送
   - 快捷键绑定
   - 快速回复面板

4. **数据存储**
   - SQLite + Room数据库
   - 话术数据本地存储
   - 云同步功能（可选）

5. **权限系统**
   - 多级权限管理
   - 管理员/小组长/普通用户权限
   - 角色权限分配

## 项目结构

```
YuPinBioQuickReply/
├── app/
│   ├── src/main/java/com/yupinbio/quickreply/
│   │   ├── MainActivity.java          # 主界面
│   │   ├── FloatWindowService.java    # 悬浮窗服务
│   │   ├── DatabaseHelper.java        # 数据库管理
│   │   ├── PhraseManager.java         # 话术管理
│   │   ├── PermissionManager.java      # 权限管理
│   │   └── SearchActivity.java        # 搜索界面
│   ├── src/main/AndroidManifest.xml   # Android配置文件
│   └── build.gradle                   # Gradle配置
├── .github/workflows/android.yml      # GitHub Actions
├── README.md                          # 项目说明
└── assets/
    ├── phrases_data.json              # 话术示例数据
    └── images/                        # UI图片资源
```

## GitHub Actions配置
自动编译APK，下载链接在Actions页面