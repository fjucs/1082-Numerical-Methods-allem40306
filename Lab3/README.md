# 題目
寫出 Lagrange, NewtonDividedDifference, GrogoryNewtonForward, GrogoryNewtonBackward, GaussForward, GaussBackward，並和實驗數據比對

# 執行說明
* 程式碼：main.py
* 測資：test1(2)-`problem_number`.txt
* 結果：`algorithm_name``problem_number`.png
* `problem_number`
    * 1:公共題
    * 2:3e^xsin(x) + cos(x) + 6.9
    * 3:4x^2sin(x) - 3cos(x) + 7.5
    * 4:2e^(2x) + 7sin(x) + 8.8
    * 5:4.4e^(sin(x)) - 9.6

* 運行方式
    * 利用 command 執行 main.py
    * 輸入想看的題目號碼 (1~5)
    * 會產生出相對應圖片，紅色代表由 Interpolation 函式所產出的結果，黃色代表油原函式產生出的結果