# データフレーム同士の外部結合
データフレーム1とデータフレーム2を外部結合する

<br>

## データフレーム(1)を表示
```
frame1
```
![画像1](./Pandas-Exercises5-1.png)

<br>

## データフレーム(2)を表示
```
frame2
```
![画像2](./Pandas-Exercises5-2.png)

<br>

## データフレーム同士の外部結合
```
main = pd.merge(frame1, frame2, how='left', on='COL3')
```

<br>

## 結合済みのデータフレーム表示
```
main
```
![画像3](./Pandas-Exercises5-3.png)
