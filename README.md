# vue-debug

vue 是一个 git 子仓库

```shell
cd vue
pnpm i
pnpm run build --sourcemap --types
```

```shell
cd app
pnpm i
# 启动 5173 端口，与 vscode 调试端口一致，如修改端口则需同步 .vsocde/launch.json 配置
pnpm run dev
```

使用 vsocde 的调试面板启动调试
