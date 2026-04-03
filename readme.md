TV上播放电台，代码来自transistor3.24


1. 解决 lint 检查失败的问题 ：
   
   - 在 app/build.gradle 文件的 lintOptions 中添加了 disable 'ExpiredTargetSdkVersion' 配置
   - 这禁用了 Google Play 要求 target API level 31 或更高的 lint 检查
2. 之前的修复 ：
   
   - 升级了 Gradle 版本从 5.4.1 到 7.6
   - 移除了 gradle.properties 中的 -XX:MaxPermSize=512m 参数
   - 添加了必要的 --add-opens 参数来解决 Java 模块系统的访问问题
   - 升级了 Android Gradle 插件 (AGP) 版本从 3.5.3 到 7.4.2
   - 更新了 app/build.gradle 文件以适应 AGP 7.0+ 的语法
   - 添加了 AndroidX 支持的配置
files2AI python
#!/usr/bin/env python3
"""
项目代码处理器（最终版）
- 输出文件名为 <项目名>-AI.txt
- 输入输出目录自动同步
- 代码、JSON、PDF、Word 分别控制，默认仅代码勾选
- 自定义扩展名（逗号分隔）自动处理
- 自动处理与记忆功能
"""


    def on_closing(self):
        """窗口关闭时保存配置"""
        self.save_config()
        self.destroy()

if __name__ == "__main__":
    app = App()
    app.mainloop()
