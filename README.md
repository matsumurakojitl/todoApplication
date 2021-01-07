#TODOApplication
====

Overview

## Description
TODOを管理するためのアプリケーションです。

## Requirement
Java 11
MySQL 5.7

## Usage
トップページからはTODOの登録、未達成と完了の切り替えができます。
また、TODOの検索や編集は、トップページのリンクから飛ぶことで操作できるようになります。

## Install
ターミナルで以下のコマンドを打ち込んでください。
git clone git@github.com:team-lab/matsumurakouji-todo.git
cd matsumurakouji-todo/matsumurakouji-todo
gradle bootRun

<==========---> 80% EXECUTING [57s]
ログでは以上のように実行割合は100%にはなりません。
起動してから10~20秒ほど経過してターミナルに新しいログが表示されなくなれば起動できています。

アプリが起動したら
[localhost:8080](http://localhost:8080/)にアクセスするとトップページが表示され、このアプリを使用できるようになります。

## Author

[matsumurakoujitl](https://github.com/team-lab/matsumurakouji-todo)
