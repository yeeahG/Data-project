### Word cloud

![littleprince](https://user-images.githubusercontent.com/97449025/165537059-5b32c996-3542-41e9-b82c-5e774e1356a3.png)

- Error  
```
'cp949' codec can't decode byte 0xe2 in position 236: illegal multibyte sequence
```
file open 시 open(file_name)으로만 코드를 작성했었는데  
```
open('file_name', encoding='UTF8')
```
으로 encoding을 추가하니까 해결이 되었다
