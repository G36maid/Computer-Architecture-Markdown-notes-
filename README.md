# Computer Architecture Markdown notes 

These notes are generated using the [pptx2md](https://github.com/ssine/pptx2md) tool, which converts course slides into markdown format.

## (2024 NTU 計算機結構 筆記)

### 課程基本資訊

| 項目           | 內容                          |
| -------------- | ----------------------------- |
| 課程名稱       | 計算機結構                    |
| 開課學期       | 113-1                         |
| 授課對象       | 資訊工程學系                  |
| 授課教師       | 洪士灝                        |
| 課號           | CSIE 3340                     |
| 課程辨識碼     | 902 46100                     |
| 班次           | 02                            |
| 學分           | 3                             |
| 全/半年        | 半年                          |
| 必/選修        | 必帶                          |
| 上課時間       | 星期二 2,3,4 (9:10~12:10)     |
| 上課地點       | 資103                         |
| 備註           |                               |

## 課程大綱

### 課程概述

本課程概括計算機系統硬體及軟體運作的基礎觀念。這是一個範圍很大、內容很多的課程，課程裡只用到基本的數學，沒有幾個小學生沒看過的公式，課程的重點在告訴各位，計算機系統在過去四十年為什麼能突飛猛進? 為何能不斷地以幾何級數增快他的運算速度? 過程中遇到過甚麼難題和挑戰? 計算機結構專家 (computer architects)，是如何運算他們的經驗和智慧，去分析和解決問題?

這些經驗和智慧，至今還不斷在迅速成長與累積，在現今台灣資訊電子業必須從代工產業轉變升級為創新系統設計產業的趨勢裡，重要性與日俱增。Computer architects在台灣未來資訊電子產業中，勢必扮演舉足輕重的角色。身為【資訊工程】專業的同學們，學好計算機結構，可以清楚知道電腦的運作原理，軟硬體各部分的機能，軟硬體模組之間的互動和影響，以至於能理解行動裝置和雲端系統的來龍去脈，進而學習如何針對特定應用設計出最佳的計算機系統。

這門課程是資工系大學部學生的必修課程，也是許多進階課程的基礎。這們課程中，可以學習的東西很多，在大學部的課程中，學生由了解指令集架構 (instruction set architecture) 的設計開始，去分辨簡單指令集電腦 (RISC) 和複雜指令集電腦 (CISC) 的不同與優劣之處。進一步再去學習電腦中各個部份的設計原理，各個部份之間的相互關係，以及電腦整體運作的效能。

這門課對於有興趣修習進階的電腦系統設計、高等作業系統核心運作、平行與分散式系統，以及實際改進電腦系統應用，都有很大的助益。

### 課程目標

1. 以組合語言去深入認識電腦硬體與軟體的運作介面。
2. 了解電腦中的主要組件的設計及運作方式。
3. 熟悉CPU內部處理指令的管線以及記憶體的的架構。
4. 對於電腦系統架構，包括多核心處理機、網路、輸出入週邊裝置等之構成與相互關係。

### 課程要求

修課前，學生必須先對於下列項目有足夠了解：

- 組合語言與C語言。
- 計算機概論。
- 數位設計。

每位學生線上繳交必須使用電腦的作業以及上課小考（約佔50％）。參加實體期中考與期末考（合計50％）。以上的成績計算方式，在課程進行中可能視狀況而有所修改，教授保有修改的權利。

### 預期每週課後學習時數

3 hours

### 參考書目

#### 指定閱讀

David A. Patterson and John L. Hennessy. 2017. *Computer Organization and Design RISC-V Edition: The Hardware Software Interface* (2nd. ed.). Morgan Kaufmann Publishers Inc., San Francisco, CA, USA.

## 課程進度

| 週次  | 日期   | 單元主題                                      |
| ----- | ------ | --------------------------------------------- |
| 第1週 | 9/3    | Chapter 1 Computer Abstractions and Technology 1/2 |
| 第2週 | 9/10   | Chapter 1 Computer Abstractions and Technology 2/2 |
| 第3週 | 9/17   | Holiday                                       |
| 第4週 | 9/24   | Chapter 2 Instructions: Language of the Computer 1/2 |
| 第5週 | 10/1   | Chapter 2 Instructions: Language of the Computer 2/2 |
| 第6週 | 10/8   | Chapter 3 Arithmetic for Computer             |
| 第7週 | 10/15  | Chapter 4 The Processor 1/3                   |
| 第8週 | 10/22  | Chapter 4 The Processor 2/3                   |
| 第9週 | 10/29  | Chapter 4 The Processor 3/3                   |
| 第10週| 11/5   | Midterm Exam                                  |
| 第11週| 11/12  | Chapter 5 Large and Fast: Exploiting Memory Hierarchy 1/3 |
| 第12週| 11/19  | Chapter 5 Large and Fast: Exploiting Memory Hierarchy 2/3 |
| 第13週| 11/26  | Chapter 5 Large and Fast: Exploiting Memory Hierarchy 3/3 |
| 第14週| 12/3   | Chapter 6 Parallel Processors from Client to Cloud 1/2 |
| 第15週| 12/10  | Chapter 6 Parallel Processors from Client to Cloud 2/2 |
| 第16週| 12/17  | Final Exam                                    |

## 成績評量方式

| 編號 | 項目              | 百分比 | 說明 |
| ---- | ----------------- | ------ | ---- |
| 1    | Assignment and Quiz| 30%    |      |
| 2    | Midterm Exam      | 30%    |      |
| 3    | Final Exam        | 40%    |      |

## 針對學生困難提供學生調整方式

### 調整方式

| 項目           | 說明 |
| -------------- | ---- |
| 上課形式       |      |
| 作業繳交形式   |      |
| 考試形式       |      |
| 其他           | 由師生雙方議定 |

## 面談時間

備註