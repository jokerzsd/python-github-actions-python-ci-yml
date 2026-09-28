# Python GitHub Actions 单元测试示例

这是一个最小的 Python 项目示例，演示如何使用 `pytest` 编写单元测试，并通过 GitHub Actions 在每次 push 或 pull request 时自动运行测试。

## 本地运行

```bash
python -m pip install -r requirements.txt
pytest -v
```

工作流文件位于 `.github/workflows/ci.yml`，使用 Python 3.11 和 Ubuntu runner。
