# Window powershell MD5 Search Mapping file


#### 為了搜尋全機是否有符合以下檔案，並透過MD5進行搜尋
#### 若有匹配到的話會回傳相關資訊
|FileName |MD5                             |
|-----    |--------------------------------|
|start    |986afc16d01d2c5c03022dc74433214a|
|updat3   |f86306def0ca642afe8cdd028a9b236e|
|1        |e69dc5369868c6d6b5b78c2f12829906|
|test     |edbbbf2452b456deda2e125a2ea4aa0e|
|xmring   |8618d80b774669b7358d377e00d5b0f1|


### psl 檔案搜尋位置
#### 可以調整Get-ChildItem 後面的路徑，該檔案預設為D:\

## 執行方式



#### 透過powershell執行檔案
```
.\windows_Hash_find.ps1
```
