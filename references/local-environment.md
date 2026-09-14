# 本机动画环境

先检查路径存在，再复用；不重复安装所有软件。

- Python：C:\Users\MllM\Documents\FinanceLearning\.venv\Scripts\python.exe
- 用上述 Python 的 -m manim 调用 Community Edition。
- 项目可放 C:\Users\MllM\Documents\FinanceLearning 下，每个主题独立目录；用户指定位置优先，不覆盖其他课程。
- 中文字体：Microsoft YaHei，已完成中文渲染验证。
- FFmpeg 与 MiKTeX 已安装；旧进程可能需要刷新系统和用户 PATH。特定公式包可能仍需安装，基础安装不代表所有公式已验证。
- 使用标准 venv 与 pip 环境，之前 uv 安装出现跨磁盘写入错误；不要用 uv tool run 重新创建环境。

```powershell
# 在本次动画项目目录内运行，结果保存到该目录的 media 文件夹。
& 'C:\Users\MllM\Documents\FinanceLearning\.venv\Scripts\python.exe' -m manim -ql script.py Scene1
```

依赖技能：
- C:\Users\MllM\.codex\skills\manim-skill\SKILL.md
- C:\Users\MllM\.codex\skills\manimce-best-practices\SKILL.md

visualize 路径以当前技能目录为准，不固定插件版本。
LOOPY 是可选在线工具：https://ncase.me/loopy/ 。仅在用户希望使用时操作；普通因果图可直接在对话中呈现。
