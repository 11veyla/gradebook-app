HIGH SCHOOL JOURNAL
部署方式：
1. 将 ZIP 解压。
2. 把 index.html、manifest.webmanifest、sw.js、icons/ 上传到 GitHub 仓库根目录。
3. GitHub 仓库 Settings → Pages，确认从 main 分支 / (root) 部署。
4. 用 HTTPS GitHub Pages 地址打开；Chrome 菜单中选择“安装应用”。
数据：
- 成绩沿用 localStorage 键 gradebook_v1。
- 笔记保存在 gradebook_notes_v1。
- JSON 备份同时包含成绩与笔记；旧版仅成绩数组 JSON 也可导入。
- 所有资料只存在当前浏览器/设备，不会自动同步。
注意：请在清空旧站点或卸载旧 App 前，先导出 JSON 并确认备份文件可正常导入。
