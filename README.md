graph TD
    subgraph 前端 UI
        A(Web/App - React/Android Studio)
    end

    subgraph 應用伺服器
        B(Backend - Spring Boot)
        B1(財務分析模組)
        B2(消費數據整合)
        B3(投資策略生成)
        B4(OAuth 2.0 驗證管理)
    end

    subgraph 資料庫
        C(MariaDB)
        C1(用戶數據)
        C2(消費記錄)
    end

    subgraph 外部API整合
        D(銀行API, 雲端載具, 支付API)
    end

    subgraph AI 分析模組
        E(財務建議)
        E1(複利模擬)
        E2(支出優化)
    end

    A --> B
    B --> C
    B --> D
    B --> E
