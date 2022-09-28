# A quick glance of Jupyter Notebook and Python

Jupyter Notebook is a server-client application that allows you to edit your code through a web browser.<br>
Some pros of coding Python on Jupyter Notebook list below.
<li> Execute every single cells respectively.<br>
In my opinion, this might be the best benefit of choosing Jupyter Notebook as your editor.<br>
You are able to execute a portion code instead of whole part of code in your file and get the result of every single cell after you run the cell.<br>
To elaborate, thinking of the following situation, you can load local data in the first cell, ploting your data on the figure in second cell, connecting database in tthe next cell, etc.<br>
  
![未命名](https://user-images.githubusercontent.com/23008522/191406268-1c12e983-8a12-4ce9-911a-61871190e16f.png)
<li> Able to plot figure on web browser which some popular IDE don't support.
<li> An Ipython file is regarded as presentation file.<br>
You can add Markdown between your code or cell. It calls "Notebook" after all.

# Contents
- <h3>Jupyter Notebook</h3>

  - 開啟Jupyter Notebook 方式
  - 更改開啟Jupyter Notebook 預設的瀏覽器
  - Notebook內存容量過大、開很慢解決辦法 (發生在第一次執行程式碼有大量output後第二次開啟時)
  - Jupyter Notebook 快捷鍵【Esc+A、Esc+B、Esc+D+D、Esc+S、Esc+Z】
  - 顯示目前.ipynb檔案存放位置
- <h3>Python</h3>

  - Pandas 資料型態 【Series、DataFrame】
  ![Python Pandas 關係](https://user-images.githubusercontent.com/23008522/191424772-c997c7e1-a17f-4884-b1d6-73a0654396ad.png)
  - 資料表來源
    - 1.自行從0建立資料表
    - 2.外部來源導入資料。讀取、匯出資料【read_csv、to_csv、read_excel】
  - DataFrame【shape、columns、info、head、tail、dtypes】
  
  - 選取資料
    - Series【df.欄位名稱、df[欄位名稱]】
    - Series【isin(列表)、str.contain(字串/符號)、str.startswith(字串/符號)、str.match(字串/符號)、str[索引]】
    - DataFrame【df[[欄位名稱]]、df[索引值]】
    - DataFrame【df[df[欄位名稱]條件]、loc、iloc】
    
  - 資料表合併
    - DataFrame【concat、append、merge】(left、right、inner、outer)
    
  - 處理資料
    - 更改欄位名稱【rename】
    - 新增欄位
    - 移除欄位【drop】
    - 取代欄位值 【replace】
    - 缺失值【isnull、notnull、isna、dropna、fillna】
    - 唯一值【nunique】、【value_counts】
    - 重複值【duplicated、drop_duplicated】
    - 資料型態轉換【astype(int)、astype(float)、astype(str)、pd.to_datetime、dt.ymd】
    - 欄位展開 Series【str.split(符號)】
    - 轉置【melt、T or transpose、stack、unstack】
    - 排序【sort_values】(預設ascending=True)
    - 群組【groupby、agg】
    - 樞紐表【pivot_table】
    
<p align="center"><strong> 群組【groupby、agg】 圖示</strong></p>

![image](https://user-images.githubusercontent.com/23008522/191426370-a3e2ddb3-99f7-4383-b443-12c07c9cab31.png)

![image](https://user-images.githubusercontent.com/23008522/191426393-b8f1a38f-bbc7-4629-8fb0-e60abb1a183b.png)

Reference：https://zhuanlan.zhihu.com/p/101284491

<p align="center"><strong> 資料表合併圖示</strong></p>
<p align="center">(left、right、inner、outer)</p>

![image](https://user-images.githubusercontent.com/23008522/191426433-a809adb1-ce40-4fe4-a32c-92f73855e712.png)

<p align="center"><strong> 樞紐表【pivot_table】圖示</strong><p>

![pivot_table](https://user-images.githubusercontent.com/23008522/191425900-0682a0ae-17d3-44de-99de-87356d354c8f.png)

Reference：https://pbpython.com/pandas-pivot-table-explained.html
