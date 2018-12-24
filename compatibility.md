Nevolution should work on any AOSP-compatible Android devices.

There're a few exceptions: (mainly due to OEM-specific changes to the Android framework)

- MIUI Global: Nevolution must be excluded from Battery Saver to keep it working. Open system Settings - Battery & Performance - Battery Saver - Choose Apps - Select "Nevo" - Choose "No restrictions".

  - MIUI 10: Works fine
  - MIUI 9: Lacks some functionality of Notifications shade. Basic functionality should work.

- MIUI China（中国版）: 须关闭系统对女娲石的省电优化以允许其在后台工作。进入系统设置 - 电量和性能 - 应用智能省电 - 应用配置 - 选择 Nevo - 改为“无限制”。

  - MIUI 10: 兼容。为改善视觉体验，请考虑在规则中添加插件“MIUI 优化”。
  - MIUI 9: 缺少一些通知栏功能，基本功能可用。

If you found other compatibility issue, please open an issue to report.
