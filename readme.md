# How to run

## 1. run virtualenv
```
pip install virtualenv
virtualenv venv
virtualenv -p /usr/local/bin/python3 venv #指定解释器
source venv/bin/activate #激活环境，激活后可以pip安装各种包了
pip install -r requirements.txt #重新安装requirements里的包
deactivate #关闭
```
