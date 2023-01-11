Framework: Rasa

conda: Quản lý thư viện trên máy

### Tạo môi trường
```
conda create -n chatbot_rasa
```

### Activate môi trường
```
conda activate chatbot_rasa 
```

### Cài python cho môi trường 

- python 3.7 ổ định
- Dùng cmd và môi trường conda cần cài)
```
$ conda install python=3.7
```

### Cài rasa(Phiên bản mới nhất):
```
$ pip install rasa
```

### Khởi tạo chatbot
```
$ rasa init
```

data/
    + nlu 
        ++ intent: Ý định

# Câu lệnh rasa
## Traing lại model:
```
$ rasa train
```

## Check bot có trả lời đúng hay không
```
$ rasa shell
```


