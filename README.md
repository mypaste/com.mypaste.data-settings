# 数据设置

MyPaste extension `com.mypaste.data-settings` (version `1.0.3`).

备份与恢复、历史导入导出、设置文件与诊断；界面由随包扩展提供，文件选择、校验与写入仍由宿主完成。

This repository is an independent copy extracted from the former `mypaste-code-extensions` monorepo at commit `2af6675ab1473c9e38146ea0b6da68256a293440`. It contains only this extension's tracked source files. The published `.mypaste-plugin` archives and marketplace index live in [`mypaste-extensions-catalog`](https://github.com/mypaste/mypaste-extensions-catalog).

The manifest speaks MyPaste plugin protocol v3. Installation, capability mediation, and content-digest verification are performed by the MyPaste desktop host.

## Files

- `mypaste.plugin.json`: package identity and capability declaration.
- `run.sh`, `src/`, `panel.html`, or `run`: package implementation.

## License

MIT. See [LICENSE](LICENSE).
