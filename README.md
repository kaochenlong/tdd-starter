# TDD Starter

使用 Jest 學習 Test-Driven Development（TDD）的練習專案。

## 安裝

```bash
npm install
```

## 執行測試

```bash
# 執行所有測試
npm test

# Watch 模式（檔案變動自動重跑）
npm run test:watch
```

## TDD 循環

1. **Red** - 先寫一個會失敗的測試
2. **Green** - 寫最少的程式碼讓測試通過
3. **Refactor** - 重構程式碼，保持測試通過

## 目錄結構

```
├── src/          # 原始碼
├── __tests__/    # 測試檔案
└── package.json
```

## 練習題目：銀行帳戶

### 存錢功能

- 可以存錢
- 不可以存 0 元或是小於 0 元的金額（越存錢越少！）

### 領錢功能

- 可以領錢
- 不能領 0 元或是小於 0 元的金額（越領錢越多！）
- 不能領超過本身餘額

by eddie@5xcampus.com
