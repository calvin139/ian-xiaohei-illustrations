# Chibi Character Icon Assets

这个目录存储原创 Chibi 角色头像资产。

## 文件说明

### chibi-character-concept.svg
**概念图/参考设计**

这是一个 SVG 格式的概念设计，展示 Chibi 角色的设计元素和比例：
- 大头小身体的构成
- 头部配饰（原创技术风格）
- 半眯眼的神秘表情
- 浮动装饰元素的位置
- 色彩调性（冷色系、柔和蓝紫）
- 软笔触效果的示意

**用途**：
- 设计参考
- 比例和布局指南
- 迭代时的视觉对标

**注意**：这是 SVG 矢量图，实际生成的高质量版本应使用以下资源。

## 生成高质量版本

### 使用 AI 图像生成工具

使用 `references/chibi-character-prompt.md` 中的完整提示词和以下工具生成高质量版本：

1. **Midjourney** - 推荐，擅长风格一致性
2. **DALL-E 3** - 推荐，细节丰富
3. **Stable Diffusion** - 本地可控
4. **Claude** - 内置生成能力

详见 `chibi-character-generation-guide.md`

### 手绘版本

如需完全创意控制或手绘风格，参考 `references/chibi-character-style.md` 使用以下工具：
- Krita
- Procreate
- Clip Studio Paint
- Photoshop

## 文件命名规则

新生成的资产应按以下格式命名：

```
chibi-character-v{version}-{description}.{format}
```

示例：
- `chibi-character-v1-cool-developer.png`
- `chibi-character-v2-tech-mysterious.png`
- `chibi-character-final-512x512.png`

## 版本管理

- 保留所有版本便于比较和回滚
- 每个迭代使用新的版本号
- 在文件名中注明主要修改或特征

## 使用场景

- ✅ GitHub 用户头像
- ✅ 社交媒体头像（Twitter, LinkedIn, Discord 等）
- ✅ 个人博客头像
- ✅ 社区论坛头像
- ✅ 开发者身份标识

## 技术规格

### 推荐规格
- **格式**：PNG（带透明背景）或 JPG（白色背景）
- **尺寸**：512x512px（高分辨率）
- **比例**：1:1（方形）
- **色彩空间**：RGB
- **背景**：纯白或透明

### 缩放可读性
生成的角色应在以下尺寸下保持清晰可认：
- 512x512px - 完整细节
- 256x256px - 主要特征清晰
- 128x128px - 清晰可认
- 64x64px - 可认（主要轮廓）

## 设计参考文档

| 文档 | 位置 | 用途 |
|------|------|------|
| 设计指南 | `references/chibi-character-style.md` | 详细的视觉规范和限制 |
| 生图提示词 | `references/chibi-character-prompt.md` | AI 生成用的完整提示词 |
| 生成指南 | `chibi-character-generation-guide.md` | 如何使用提示词生成资产 |

## 质量检查

生成后验证：
- [ ] 1:1 方形比例
- [ ] 大头小身体设计
- [ ] 半眯眼表情清晰
- [ ] 原创头部配饰
- [ ] 浮动装饰元素可见
- [ ] 冷色系调性
- [ ] 水彩/手绘感明显
- [ ] 64x64px 下可认
- [ ] 无版权问题
- [ ] 技术元素微妙

## 许可证

所有生成的 Chibi 角色资产按照项目主许可证（见项目根目录 LICENSE）发布。

如使用第三方 AI 生成，请遵守相应工具的使用条款。
