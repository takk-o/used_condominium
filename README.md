# used_condominium

## Overview
Excelシートで指定した都道府県、市区町村の中古マンションの物件情報（マンション名、住所、交通、築年数、階建て、総戸数）を検索サイトより収集し、同シート上に出力する。

## Requirements
- Python 3.9.6
- requests 2.31.0
- bs4 0.0.2
- openpyxl 3.1.2

## Usage
1. used_condo.xlsxの都道府県("C2")、市区町村("E2")を登録
1. used_condominiumを起動
1. used_condo.xlsxのDetail行（６行目以降）に該当物件が取得される

## Author
- takk-o
- Mail : ynurmj5e@gmail.com
