# 反霸屏卫士 v10 / Anti-Baping Guardian v10

一款面向网课党的 Windows 反霸屏小工具，主打**低存在感、静默运行、反侦察**。默认不弹窗、不抢桌面、不改窗口外观，只在后台默默处理霸屏窗口，尽量降低被教师端识别的概率。

## 中文简介

- **静默守护**：普通模式只做「任务栏置顶 + 焦点守护」，动作轻、痕迹小，日常挂机不易被察觉。
- **反侦察友好**：不最小化、不压底、不改窗口样式，避免触发教师端「异常窗口」检测。
- **可选防最小化**：阻止霸屏软件因检测到遮挡而自动最小化，保持界面稳定。
- **可选键盘释放**：解开被锁定的 Win 键等快捷键，随时切窗口、开浏览器。
- **可选活动伪造**：定时注入无害键盘事件，让教师端看到你「一直在活跃」，而不是长时间无操作。
- **进阶模式**：一键挂起霸屏进程全部线程，彻底冻结，停止后自动恢复。
- 启发式识别 + 系统窗口白名单，误伤少；配置持久化，日志轮转，崩溃可追溯。

> 仅用于学习与个人研究，请遵守学校与平台规定。

## English

A lightweight Windows anti-screen-lock tool built for students in online classes, focused on **stealth, silence, and low detectability**. It runs quietly in the background without pop-ups, desktop hijacking, or visible window changes, minimizing the chance of being flagged by classroom-control software.

- **Silent guard**: Normal mode only pins the taskbar and guards focus — light-touch, low-profile, easy to leave running unnoticed.
- **Stealth-friendly**: Never minimizes, pushes down, or restyles windows, avoiding "abnormal window" detection.
- **Optional anti-minimize**: Stops screen-lock tools from auto-minimizing you when they detect overlap.
- **Optional key unlock**: Releases locked Win-key shortcuts so you can switch windows freely.
- **Optional activity faker**: Injects harmless keyboard events so the teacher-side dashboard sees you as "active" instead of idle.
- **Advanced mode**: Suspends all threads of the screen-lock process for a full freeze, auto-resumed on stop.
- Heuristic detection + system-window whitelist for fewer false positives; persistent config, rotating logs, crash tracing.

> For learning and personal research only. Follow your school's and platform's rules.
