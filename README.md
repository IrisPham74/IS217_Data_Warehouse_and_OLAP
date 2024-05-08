# ĐỒ ÁN: XÂY DỰNG KHO DỮ LIỆU PHÂN TÍCH XU HƯỚNG PHIM ẢNH TRÊN NỀN TẢNG TOÀN CẦU TMDB
State: In progress
## Thành viên nhóm:
| Họ và tên     | MSSV          |
| ------------- | ------------- |
| Ngô Đức Hoàng Hiệp  |  21520846 |
| Phạm Thị Trâm Anh  | 21520146  |
## Dataset:
Link (kaggle): https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies
## Database:
Link (ggdrive): https://drive.google.com/drive/folders/1oh-qLWDDheHbkVyqjRIKNe6MDLlVtKXY?usp=drive_link
## (Demo) PowerBI
![plot](https://github.com/IrisPham74/IS217_Data_Warehouse_and_OLAP/blob/main/reportTrending.png)
- Budget and Revenue trending by quarter and year.
- Budget-Revenue Relationship: There are points where the budget line peaks above the revenue line, suggesting periods of higher investment without proportional returns. In term of the similar line trending, budget and revenue seem to have the relatively positive correlation.
- The graph may exhibit seasonal patterns, with certain quarters showing consistent peaks or dips, which could be due to seasonal releases and audience spending habits (noteably 2nd quarter).
- Perhaps those movies have been recently released since 4th quarter of 2023, therefore, the revenue is stably close to 0. Meanwhile, some of movies are probably in rumor state or planning, so the budget is pretty low.
  
![plot](https://github.com/IrisPham74/IS217_Data_Warehouse_and_OLAP/blob/main/scatterplot.png)
- Budget-Popularity Correlation: There seems to be a positive correlation between the budget and popularity, indicating that generally, movies with higher budgets tend to be more popular.
- Language Influence: The distribution of data points across languages suggests that language may play a role in a movie’s popularity, with some languages (espcially english) showing higher popularity at lower budgets.
