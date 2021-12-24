---
title: "Django-practice"
date: 2021-12-20T22:55:05+09:00
draft: true
---

# Django一通り動かしてみためも

## 動機
- 一から触ってからだいぶ忘れたから。

## 参考書籍
- 現場で使えるDjango_基礎
- 現場で使えるDjango_発展

## ディレクトリ構成
- 現場で使えるDjango_基礎

こちらの推奨しているベストプラクティスで作ってます。

プロジェクト名をconfigとして設定ディレクトリにします。
```
mkdir django-practice
cd django-practice
django-admin startproject config .
```
## アプリ
アプリの作成
アプリにないにもurl.py
```
python3 manage.py startapp todo

```
### テンプレート
django-practice直下にテンプレートディレクトリを作ります。
```
mkdir templates
```

### static
```
mkdir static
```
