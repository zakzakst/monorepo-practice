# monorepo-practice

```
pnpm add my-lib@workspace:*
```

```
pnpmでは
packages/
└── my-lib
を
apps/my-app/node_modules/my-lib
へ**シンボリックリンク（symlink）**として配置しています。
つまり
node_modules/my-lib は packages/my-lib を指しているだけなんです。
```