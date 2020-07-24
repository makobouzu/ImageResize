# ImageResize

画像を正方形に整形するスクリプトです。

```
python file_resize.py folder 500
```

### SetUp
```
pip install Pillow
```

### example
- resizeのみの場合
```
python file_resize.py img 500
```
```
python file_resize.py img/dataset 400
```

- resize + rotateをする場合(コード内のコメントアウトを外した状態で)
```
python file_resize.py img 500 90
```
```
python file_resize.py img/dataset 400 45
```
