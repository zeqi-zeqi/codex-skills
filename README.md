# codex-skills

Reusable Codex skills maintained by `zeqi-zeqi`.

## pixel-perfect-editable-ppt

将流程图、技术路线图、信息图、架构图或总图图片按源图原始长宽比，高保真复刻为可编辑 PowerPoint。

- 文字、边框、色块、箭头和简单几何结构使用原生 PowerPoint 对象。
- 默认情况下，照片、图标及复杂工程视觉可作为独立局部截图嵌入。
- 支持“图标图片不裁切”占位模式：只还原文字与框图，图片和图标使用可编辑方块占位。
- 截图有误时优先重新裁切，必要时使用图片生成进行局部修复。
- 不默认改成 16:9，也不允许将整张源图铺成背景冒充可编辑版本。
- 采用按需加载、批量渲染和局部复查，减少不必要的上下文与图片 token 消耗。

### Install

在 Codex 中调用 `$skill-installer`，并提供：

```text
https://github.com/zeqi-zeqi/codex-skills/tree/main/skills/pixel-perfect-editable-ppt
```

安装后可这样调用：

```text
$pixel-perfect-editable-ppt 把这张图片按原始比例完整复刻为可编辑PPT
```

不裁切图片和图标：

```text
$pixel-perfect-editable-ppt 复刻 XXX 文件夹中的总图，图标图片不裁切
```
