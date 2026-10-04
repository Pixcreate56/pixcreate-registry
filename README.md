# PixCreate Registry

PixCreate 组件库的**公开注册表**（仅含组件产物，不含设计规范与内部工具）。

## 使用（shadcn CLI）

```bash
npx shadcn@latest add https://raw.githubusercontent.com/Pixcreate56/pixcreate-registry/main/r/<name>.json
```

可用组件：
pixcreate-tokens · gradient-mesh-bg · magnetic-button · switch-toggle · split-text · tech-text · text-loop · list-shredder · slosh-gauge · scrubber-slider · dropdown-select · text-input

例：`npx shadcn@latest add https://raw.githubusercontent.com/Pixcreate56/pixcreate-registry/main/r/scrubber-slider.json`

> 使用 resolveToken 的组件请先安装 `r/pixcreate-tokens.json`（设计令牌库）。

组件均为自研重写（单文件 + 同名 CSS 规范），遵循 PixCreate 设计体系。
