# 手机上传 + 云端编译

1. 在 GitHub repo 页面点 **Add file → Upload files**。
2. 把这个工程包解压后，上传**里面的内容**到 repo 根目录；不要再套一层文件夹。
3. 最终 repo 根目录应该直接看到：
   - `.github/`
   - `app/`
   - `build.gradle.kts`
   - `settings.gradle.kts`
4. Commit 到 `main`。
5. 打开 repo 的 **Actions**，点 `Build Bubble Mermaid APK`。
6. 等绿色 ✅ 后打开这次 run，在 **Artifacts** 下载 `BubbleMermaid-debug-apk`。
7. 下载得到 zip，手机解压后点 `app-debug.apk` 安装。
8. 第一次打开 Bubble Mermaid，点“启动泡泡人鱼”，授权“显示在其他应用上层”，再返回 App 点一次启动。

如果 Actions 没自动开始，可进 workflow 页面点 **Run workflow**。
