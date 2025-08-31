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

## 測試結果
============================= test session starts =============================
collecting ... collected 5 items

tests.py::test_add PASSED                                                [ 20%]
tests.py::test_subtract PASSED                                           [ 40%]
tests.py::test_multiply PASSED                                           [ 60%]
tests.py::test_divide PASSED                                             [ 80%]
tests.py::test_divide_by_zero PASSED                                     [100%]

============================== 5 passed in 0.02s ==============================

Process finished with exit code 0
