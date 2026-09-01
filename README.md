# codex-skills

Reusable Codex skills maintained by `zeqi-zeqi`.

## pixel-perfect-editable-ppt

将流程图、技术路线图、信息图、架构图或总图图片按源图原始长宽比，高保真复刻为可编辑 PowerPoint。

- 文字、边框、色块、箭头和简单几何结构使用原生 PowerPoint 对象。
- 照片、图标及复杂工程视觉可作为独立局部截图嵌入。
- 截图有误时优先重新裁切，必要时使用图片生成进行局部修复。
- 不默认改成 16:9，也不允许将整张源图铺成背景冒充可编辑版本。

### Install

在 Codex 中调用 `$skill-installer`，并提供：

```text
https://github.com/zeqi-zeqi/codex-skills/tree/main/skills/pixel-perfect-editable-ppt
```

安装后可这样调用：

```text
$pixel-perfect-editable-ppt 把这张图片按原始比例完整复刻为可编辑PPT
```
