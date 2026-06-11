# VESTA Network (AWS)

## 概要
本リポジトリはVESTA環境のVPC構成を管理する。

## 構成
- オンライン・バッチ処理用VPC
- 帯域制御用VPC

## 除外
- IGW
- NAT Gateway
- VPC Endpoint
- Transit Gateway

## 方針
- 閉域ネットワーク前提
- サブネットは用途別に分離
- 命名規則は社内標準に準拠

## ディレクトリ構成
``