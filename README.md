# Migrate phone number

**Tool hổ trợ chuyển đổi số điện thoại 11 số sang 10 số.**

[![Latest Stable Version](https://poser.pugx.org/vxm/migrate-phone-number/v/stable)](https://packagist.org/packages/vxm/migrate-phone-number)
[![Total Downloads](https://poser.pugx.org/vxm/migrate-phone-number/downloads)](https://packagist.org/packages/vxm/migrate-phone-number)
[![Build Status](https://travis-ci.org/vuongxuongminh/migrate-phone-number.svg?branch=master)](https://travis-ci.org/vuongxuongminh/migrate-phone-number)
[![Code Coverage](https://scrutinizer-ci.com/g/vuongxuongminh/migrate-phone-number/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/vuongxuongminh/migrate-phone-number/?branch=master)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/vuongxuongminh/migrate-phone-number/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/vuongxuongminh/migrate-phone-number/?branch=master)
[![PHP7](https://img.shields.io/badge/Powered_by-PHP_7.1-green.svg?style=flat)](http://php.net)

Tool được xây dựng để phục vụ việc chuyển đổi dữ liệu số điện thoại từ 11 số sang 10 số.
Tool hổ trợ chuyển đổi trên các CSDL phổ biến như `mysql, postgres, sql server...` và 
`spreadsheet (xls, xlsx, csv...)`.

## Yêu cầu
* [PHP >= 7.1](http://php.net)

## Cài đặt

Cài đặt thông qua `composer` nếu như đó là một khái niệm mới với bạn xin click vào 
[đây](http://getcomposer.org/download/) để tìm hiểu nó.

```sh
composer global require "vxm/migrate-phone-number"
```

## Cách dùng

+ Đối với CSDL (database) thì bạn hãy gõ lệnh CMD sau:

```sh
vxm migrate:db
```

+ Đối với spreadsheet (xls, xlsx, csv...) thì bạn hãy gõ lệnh CMD sau:

```sh
vxm migrate:ss
```

## Screenshot

![1](screenshots/1.png)

## Hỏi & đáp

+ Các loại CSDL (database) nào được hổ trợ?
    - MySQL, Postgres, SQL Server, Oracle, SQLite
+ Các loại format spreadsheet nào được hổ trợ?
    - Xlsx, Xlsm, Xltm, Xls, Xlt, Ods, Ots, Slk, Xml, Gnumeric, Htm, Html, CSV
+ Đối với các trường dữ liệu đặc biệt số điện thoại nằm bên trong chuỗi JSON thì có được hổ trợ không?
    - Có
