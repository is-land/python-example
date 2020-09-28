##PYTHON ETL

### 說明 

使用 kaggle dataset https://www.kaggle.com/datasnaek/youtube-new

0. 列出所有影片的類別 

0. 列出 所有 rap 影片 的dislike 數目

0. 找出發布時間與地區 和 喜歡人數的線性關係

0. 排序出最多人不喜歡的前十名種類影片

0. 排序出前十名的類別  喜歡 和 不喜歡的比例 擁有最大的變異數

### ETL Pandas 
#####Python version : 3.8.5
 
####設定 你下載的dataset 路徑

    DATA_PATH="./yt/" 
    
    the path have files:
    ./yt/CA_category_id.json
    ./yt/JP_category_id.json
                .
                .

#####依賴檔
    ETL_pyspark_requirements.txt

執行jupyter 
