# FAERS Pharmacovigilance Analysis

![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![Quarto](https://img.shields.io/badge/Quarto-39729E?logo=quarto&logoColor=white)
![Healthcare](https://img.shields.io/badge/Healthcare-009688)
![Reproducible Workflow](https://img.shields.io/badge/Reproducible-Workflow-success)

Data files are not included.
Download the relevant quarterly files from the FDA website and place them in the data folder before rendering the report.

Everything can be reproduced except the adverse effects analysed further are hard-coded to fatigue and death.
ROR calculated therefore will be the most frequently reported drugs for fatigue and death respectively.

## Full Report
[Exploring Potential Drug Safety Signals Using the FDA Adverse Event Reporting System (FAERS)](https://reinasdatastudio.github.io/faers-pharmacovigilance-analysis/FAERS_Report.html)

## YouTube
- [FDA AEMS (FAERS) Analysis in R (Part 1) | Data Cleaning and Preprocessing](https://youtu.be/g4BIA83Us6Q)
- [FDA AEMS (FAERS) Analysis in R (Part 2) | Joining data, Visualisation and ROR](https://youtu.be/ZY7ZhC5v8_w)

## Overview

This project explores potential drug safety signals using the FDA Adverse Event Reporting System (FAERS).

The analysis demonstrates:

- Data cleaning of large healthcare datasets
- Dataset integration using primary identifiers
- Exploratory adverse event analysis
- Reporting Odds Ratio (ROR) calculations
- Reproducible reporting using Quarto

## Tools

- R
- tidyverse
- ggplot2
- pvda
- Quarto

## Data Source

FDA Adverse Event Reporting System (FAERS)

## Outputs

- Quarto report
- Data visualisations
- ROR analysis

## Author

Reina Kaino

Former Pharmacist | Data Scientist | System Engineer

**Website**
https://reinasdatastudio.github.io/webpage/

&ensp;

---

&ensp;

# FDA有害事象報告システム（FAERS）を用いた医薬品安全性シグナルの探索

本リポジトリでは、FDA Adverse Event Reporting System（FAERS）の公開データを用いて、Rによるファーマコビジランス解析を実施しました。

本プロジェクトでは、データクリーニングからデータ統合、可視化、不均衡解析（Reporting Odds Ratio：ROR）まで、一連の解析ワークフローを再現可能な形でまとめています。

> **注意**
>
> 本解析は教育およびポートフォリオを目的としたものです。
> FAERSは自発報告データベースであり、本解析結果は因果関係を示すものではなく、安全性シグナル探索のための参考情報として解釈されるべきです。

## レポート

### 英語版

📄 [Exploring Potential Drug Safety Signals Using the FDA Adverse Event Reporting System (FAERS)](https://reinasdatastudio.github.io/faers-pharmacovigilance-analysis/FAERS_Report.html)

### 日本語版

📄 [FDA有害事象報告システム（FAERS）を用いた医薬品安全性シグナルの探索的解析](https://reinasdatastudio.github.io/faers-pharmacovigilance-analysis/FAERS_Report_ja.html)

## プロジェクト内容

* FAERSデータの読み込み
* データクリーニング
* 重複報告の処理
* DEMO・DRUG・REACデータセットの統合
* ggplot2による可視化
* Reporting Odds Ratio（ROR）による不均衡解析
* 解析結果の考察および限界の整理

## 使用技術

* R
* tidyverse
* ggplot2
* pvda
* Quarto

## ライセンス

本リポジトリはMITライセンスのもとで公開しています。

## 作成者

戒能 伶奈

元薬剤師｜データサイエンティスト

R・医療データ解析・再現可能な解析ワークフローに興味があります。

**Website**
https://reinasdatastudio.github.io/webpage/
