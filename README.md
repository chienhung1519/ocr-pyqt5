# OCR Application Using PyQT5

## Install Tesseract

https://tesseract-ocr.github.io/tessdoc/Installation.html

## Install Qt Designer

* [Windows](https://build-system.fman.io/static/public/files/Qt%20Designer%20Setup.exe)
* [Mac](https://build-system.fman.io/static/public/files/Qt%20Designer.dmg)

## Install Libraries

```bash
pip install pytesseract pyqt5 pyinstaller
```

## Pyinstaller

```bash
pyinstaller --onedir --windowed --icon=./icon.ico --add-data="./icon.png;." app.py
```

* Copy relevant poppler files to dist\app\_internal\bin
* Copy unstructured site-package to dist\app\_internal
* Copy unstructured_pytesseract site-package to dist\app\_internal

## Reference

* [使用 Qt Designer](https://steam.oxxostudio.tw/category/python/pyqt5/qt-designer.html)