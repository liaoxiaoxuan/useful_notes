# TERMINAL

## 進入venv

1. 點選任一附檔名為「.py」的檔案
2. 視窗又下角出現「venv」就是進入了venv



```bash # 一種 terminal 的語法
python -m venv venv # 創建(venv)虛擬環境(venv)
D:\PYTHON\yourfoldername\venv\Scripts\Activate.ps1 # 進入虛擬環境(venv)
```


## venv setting
On Windows, it may be required to enable this Activate.ps1 script by setting the
execution policy for the user. You can do this by issuing the following PowerShell
command:

PS C:\> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
（↑以系統管理員身分執行）