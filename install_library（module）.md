# 如何安裝套件／函式庫／模組

```bash
pip install "套件／函式庫／模組的名稱"
pip freeze   # 顯示已安裝的套件
pip freeze > requirements.txt   # 將已安裝的套件寫入 requirements.txt 檔
pip install -r requirements.txt   # 安裝寫在 requirements.txt 檔裡的所有套件（專案搬家用）
pip install -U "套件／函式庫／模組的名稱"   # 更新版本
python.exe -m pip install -U pip   # 更新 pip 版本
pip install --upgrade pip   # 去除 WARNING: There was an error checking the latest version of pip. 警告
```