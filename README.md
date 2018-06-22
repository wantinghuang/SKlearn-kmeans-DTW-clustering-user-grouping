# 2017 Smart Grid Big Data Analytics Competition 

A project to analyze power usage data offered by Taiwan Power Cooperation in 2017 Smart Grid Big Data Analytics Competition

低壓智慧電表大數據分析與設計競賽。針對歷史用電資料，利用數值分析等方法，提出具學術或應用價值的研究

## INTRO (in English)

The goal of this project is to find some useful information through out the history data of power usage and some open data(e.g. weather data).
We use clustering method to form groups and later we will build deep learning(SVR, RNN, LSTM) model to predict power usage.
This repository focus on how to do clustering.

* 本篇著重於如何做分群，不包含預測用電量的檔案。

## 競賽內容

利用本次競賽所提供的一年期間，每15分鐘低壓智慧電表資料，自行搭配氣象資料等，進而利用數值分析或演算分析個體或全體住戶的用電行為，例如用電量預測、用電特徵、不同區域比較或節電建議…等 (不限於此)。

### 智慧電表資料說明

開放資料內容
1.用戶類型：低壓住宅1,000戶以上
環境資訊：該資料所屬地區(縣市)、用電類型(表燈…等)。
即時用電資料：當下前15分鐘的用電能量（kWh）
歷史用電資料：去年度所有15分鐘用電能量（kWh）
電價資訊：台電現行季節電價、住商簡易時間電價方案
2.介面與格式
研析組：提供用戶一整年度歷史用電資料，格式擬為CSV。


## Authors

國立交通大學 林于翔、許睿之、楊凱期、黃揚、彭笙榕、蘇恆毅、黃婉婷、陳泓勳

## License

This project is licensed under the MIT License

    Copyright (C) <2017> <Wan-Ting Huang>


    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
