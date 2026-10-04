# PixCreate Registry

PixCreate 组件库的**公开注册表**（仅含组件产物，不含设计规范与内部工具）。

## 使用（shadcn CLI）

```bash
npx shadcn@latest add https://raw.githubusercontent.com/Pixcreate56/pixcreate-registry/main/r/<name>.json
```

可用组件（19 项）：
pixcreate-tokens · pixcreate-named-icon · gradient-mesh-bg · magnetic-button · switch-toggle · split-text · tech-text · text-loop · list-shredder · slosh-gauge · scrubber-slider · dropdown-select · text-input · **voice-pill · ai-voice-glow · loading-thought-line · nav-branched-menu · nav-segmented · tilt-card**

> 图标组件依赖 pixcreate-named-icon（自包含 SVG 版 NamedIcon，无需 Remix 数据文件）。
> 使用 resolveToken 的组件请先安装 pixcreate-tokens。

组件均为自研重写（单文件 + 同名 CSS），遵循 PixCreate 设计体系。
