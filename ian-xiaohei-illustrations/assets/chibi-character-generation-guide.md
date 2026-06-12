# Chibi 角色头像生成指南

## 概述

本指南说明如何使用 `chibi-character-prompt.md` 中的提示词生成原创 Chibi 角色头像。

## 使用方式

### 方式 1：AI 图像生成工具

使用以下任一工具，将 `chibi-character-prompt.md` 中的完整提示词复制到图像生成工具：

#### Midjourney
1. 在 Discord 中找到 Midjourney Bot
2. 使用命令：`/imagine prompt:`
3. 粘贴完整提示词
4. 等待生成（约 1 分钟）
5. 选择满意的变体并放大

#### DALL-E 3
1. 访问 ChatGPT Plus 或 DALL-E 网站
2. 粘贴完整提示词
3. 生成图像
4. 下载高分辨率版本

#### Claude (with Vision)
1. 在 Claude 对话中使用提示词
2. Claude 会使用其内置图像生成能力
3. 下载生成的图像

#### Stable Diffusion（本地）
1. 设置本地 Stable Diffusion 环境
2. 使用 WebUI 或命令行
3. 复制提示词
4. 调整采样步数和 CFG scale 以获得最佳效果

### 方式 2：手绘或数字绘图

如果希望保持完全的创意控制，使用以下工具结合 `chibi-character-style.md` 中的设计指南：

- **Krita**：开源、支持笔刷、适合水彩风格
- **Procreate**：iPad 专业绘画应用
- **Clip Studio Paint**：专业动漫绘画工具
- **Photoshop**：图像编辑、绘画和特效
- **GIMP**：开源替代品

## 生成技巧

### 获得最佳结果

1. **提示词长度**：完整提示词约 1500+ 词符，提供充分的艺术指导
2. **采样参数**（适用于 Stable Diffusion）：
   - Sampling steps: 50-75
   - CFG scale: 7-9
   - Seed: 固定种子以便迭代改进

3. **多次尝试**：不同模型和参数会产生不同结果
   - 至少生成 3-5 个变体
   - 选择最符合设计指南的版本

### 迭代改进

如果生成结果不满意，使用 `chibi-character-prompt.md` 中的编辑提示词进行改进：

- 调整表情更加神秘
- 增强技术感（保持柔和）
- 调整浮动元素布局
- 优化色彩调性

## 文件保存

### 命名约定

生成的资产应保存为：

```
ian-xiaohei-illustrations/assets/chibi-character/{version}/{filename}
```

### 文件名格式

```
chibi-character-v{version}-{style}.png
```

示例：
- `chibi-character-v1-cool-developer.png`
- `chibi-character-v2-tech-mysterious.png`

### 版本管理

- **v1**：初始生成版本
- **v2**、**v3** 等：迭代改进版本
- 保留所有版本便于比较和回滚

## 质量检查清单

生成后验证图像是否满足以下条件：

- [ ] 方形 1:1 比例
- [ ] 头身比例正确（大头小身）
- [ ] 表情传达冷静自信与神秘感
- [ ] 半眯眼设计到位
- [ ] 发型是短发、略蓬乱、分层
- [ ] 头部配饰原创、技术风格、柔和处理
- [ ] 3-5 个浮动装饰元素周围分布
- [ ] 色彩冷色系为主（蓝、青、紫）
- [ ] 水彩感、可见笔触、非矢量风格
- [ ] 软边、无硬阴影、柔和漫射光
- [ ] 背景纯白或极淡
- [ ] 缩小到 64x64px 仍清晰可认
- [ ] 无参考任何现有 IP 或品牌
- [ ] 技术/黑客元素微妙、不喧宾夺主

## 后处理

如需微调，可使用以下工具：

- **Photoshop/Affinity Photo**：局部调整色彩、对比度、饱和度
- **Krita**：笔画微调、特效添加
- **Lightroom**：全局色彩和光影调整

避免过度处理，保持原始的手绘、水彩感。

## 常见问题

### Q: 生成不出理想效果怎么办？

**A**: 尝试以下操作：
- 调整 CFG scale 和 sampling steps
- 使用不同的 AI 模型
- 多次生成，选择最佳的
- 使用编辑提示词微调细节

### Q: 可以使用生成的图像吗？

**A**: 检查 AI 工具的使用条款：
- Midjourney：商业使用需付费订阅
- DALL-E：根据订阅级别允许商业使用
- Stable Diffusion 开源模型：一般允许商业使用
- Claude：遵循其使用条款

### Q: 怎么保证完全原创？

**A**: 
- 使用详细的设计提示词指导生成过程
- 参考 `chibi-character-style.md` 中的"绝对禁止"部分
- 生成后验证与任何已知 IP 或品牌无关
- 多次迭代确保设计独特
