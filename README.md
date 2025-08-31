# Unit Test Demo

這是一個簡單的 Python 測試專案，展示如何使用 **pytest** 撰寫單元測試。

## 功能
- `add(a, b)`：加法
- `subtract(a, b)`：減法
- `multiply(a, b)`：乘法
- `divide(a, b)`：除法（支援錯誤處理）

## 如何執行測試
```bash
pip install -r requirements.txt
pytest -v --cov=src --cov-report=term-missing
