To track installed packages, you will need to run:

```bash
apm list --installed --bare > ~/.atom/package.list
```

To restore, use:

```bash
apm install --packages-file ~/.atom/package.list
```
