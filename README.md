# Line Yolo API

Sample bot for object detection

## Getting started

### Install virtualenv
```
$ pip install virtualenv
```

### Create new virtual environment
```
$ virtualenv line-yolo-api-venv
```

### Activate the virtual environment

* For Windows:
```
$ line-yolo-api-venv\Scripts\activate.bat
```

* For Mac and Linux:
```
$ source line-yolo-api-venv/bin/activate
```

### Install required packages.

* For Windows, use PIP to install pytorch based on the instruction from: https://pytorch.org/, then:
```
$ pip install -r requirements-windows.txt
```

* For Mac and Linux:
```
$ pip install -r requirements.txt
```

### Create .env file.
```
LINE_CHANNEL_SECRET='<<Your Line Channel Secret>>'
LINE_CHANNEL_ACCESS_TOKEN='<<Your Line Channel Access Token>>'
```

### Start the api.
```
$ python line-yolo-api.py
```

### Resource
```
https://karnyong.medium.com/%E0%B8%AA%E0%B8%A3%E0%B9%89%E0%B8%B2%E0%B8%87-api-%E0%B8%95%E0%B8%A3%E0%B8%A7%E0%B8%88%E0%B8%88%E0%B8%B1%E0%B8%9A%E0%B8%A7%E0%B8%B1%E0%B8%95%E0%B8%96%E0%B8%B8%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-yolov5-%E0%B8%9C%E0%B9%88%E0%B8%B2%E0%B8%99-line-%E0%B8%95%E0%B8%AD%E0%B8%99%E0%B8%97%E0%B8%B5%E0%B9%88-2-deploy-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-docker-%E0%B8%82%E0%B8%B6%E0%B9%89%E0%B8%99-heroku-cloud-93aebc543bb7
```
