# 智企·纸上留影

把你的照片变成独立、无标题的纸感版画。适合建筑、旅行、城市、水面和生活场景，也可用作手机封面。

默认只交生成图，不把原图拼进去。选择不同构图必须落实到画面；动画思路与静态画风分别介绍，不以静态图冒充动画。

## 如何使用

上传照片后说：

> 用 $zhiqi-photo-relic-editorial 把这张照片做成独立纸上留影，不加标题。

> 使用 social-cover 布局和 ink-assembly motion seed，先交一张静态成品，只要生成图，不拼原图。

不熟悉参数也可以直接问：“你负责什么，有哪些模式，怎么使用？”

## 模式怎么选

- 构图：纸上留白、大留白、中轴呼应、水平锚定、手机封面；上下拼图仅在明确要求时采用。
- 视觉语言：建筑印章、叠层秩序、天际线记忆、光影留痕、轮廓留痕。
- 笔触：柔墨、浓墨块面、细线、一点点色。
- 动画思路：仅静态、轮廓落纸、墨块组装、光影渐显。

`social-cover` 控制手机封面构图；`ink-assembly` 表示未来逐块出现的设计思路。静态只显示最终完整图，不包含动画或独立图层。

完整中文解释、适用情形和示例见 [模式与使用说明](references/modes-and-usage.md)。

## 安装

```bash
npx skills add https://github.com/xran7566-dot/zhiqi-photo-relic-editorial --skill zhiqi-photo-relic-editorial
```

也可下载整个仓库，将文件夹放入 `~/.codex/skills/zhiqi-photo-relic-editorial/`，保留 `references` 与 `agents`。菜单搜索“智企·纸上留影”；如未刷新可重启 Codex。

需要运行环境提供图像生成/编辑能力。安装本身不会生成图片，生图额度与费用由所用工具决定。

## 来源

基于 [wnby/photo-relic-editorial](https://github.com/wnby/photo-relic-editorial) 改编，保留 MIT 许可证与原作者署名。详见 [来源与改动](references/attribution.md)。原版六张示例保留在 examples/paper-beijing，其上下拼图只作历史美学参考，不是本版默认输出。发布包不含用户照片和试验生成图。
