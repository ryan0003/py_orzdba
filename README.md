# py_orzdba
# 该脚本以orzdba为原型，脚本思路完全复制orzdba，只是用python的形式展示
# 由于orzdba需要安装prel,有些机器因为版本问题，安装出现各种各样的困难，所以就用python重写了orzdba
# 如果作者觉得不合适，请联系jackey0003@hotmail.com
# 必须安装PythonMySQL和argparse模块，可以使用pip安装
# 使用方法 Python pyorzdba.py  host user password port type
# tpye = com innodb_hit innodb_rows innodb_pages innodb_data innodb_log innodb_status threads bytes 可多个一起,中间空格，例如：innodb_log innodb_status;或者单个，例如 innodb_status
