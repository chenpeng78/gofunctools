# gofunctools

[![GoDoc](https://godoc.org/github.com/chenpeng78/gofunctools?status.svg)]()
[![Go Report Card](https://goreportcard.com/badge/github.com/chenpeng78/gofunctools)]()
[![MIT licensed][3]][4]

[3]: https://img.shields.io/badge/license-MIT-blue.svg
[4]: LICENSE

使用Golang实现PHP的常见的内置函数。约140 +功能已经实现。

## 使用
```shell
go get github.com/chenpeng78/gofunctools
```

## 要求
Go 1.10 or above.

## PHP函数

### 日期时间 函数
```php
time()
strtotime()
date()
Currentdate()
checkdate()
sleep()
usleep()
GetFormattedDate()
```

### 字符串 函数
```php
strpos()
stripos()
strrpos()
strripos()
str_replace()
ucfirst()
lcfirst()
ucwords()
substr()
strrev()
number_format()
chunk_split()
str_word_count()
wordwrap()
strlen()
str_repeat()
strstr()
strtr()
str_shuffle()
trim()
ltrim()
rtrim()
explode()
strtoupper()
strtolower()
chr()
ord()
nl2br()
json_encode()
json_decode()
addslashes()
stripslashes()
quotemeta()
htmlentities()
html_entity_decode()
md5()
md5_file()
sha1()
sha1_file()
crc32()
levenshtein()
similar_text()
soundex()
parse_str()
```

### 多字节字符串 函数
```php
mb_strlen()
mb_strtoupper()
```

### URL 函数
```php
base64_encode()
base64_decode()
parse_url()
urlencode()
urldecode()
rawurlencode()
rawurldecode()
http_build_query()
```

### 数组(Slice/Map) 函数
```php
array_fill()
array_flip()
array_keys()
array_values()
array_merge()
array_chunk()
array_pad()
array_slice()
array_rand()
array_column()
array_push()
array_pop()
array_unshift()
array_shift()
array_key_exists()
array_combine()
array_reverse()
implode()
in_array()
```

### 数学 函数
```php
abs()
rand()
round()
floor()
ceil()
pi()
max()
min()
decbin()
bindec()
hex2bin()
bin2hex()
dechex()
hexdec()
decoct()
Octdec()
base_convert()
is_nan()
```

### CSPRNG 函数
```php
random_bytes()
random_int()
```

### 目录文件系统 函数
```php
stat()
pathinfo()
file_exists()
is_file()
is_dir()
filesize()
file_put_contents()
file_get_contents()
unlink()
delete()
copy()
is_readable()
is_writeable()
rename()
touch()
mkdir()
getcwd()
realpath()
basename()
chmod()
chown()
fclose()
filemtime()
fgetcsv()
glob()
```

### 变量处理 函数
```php
empty()
is_numeric()
```

### 程序执行 函数
```php
exec()
system()
passthru()
```

### 网络 函数
```php
gethostname()
gethostbyname()
gethostbynamel()
gethostbyaddr()
ip2long()
long2ip()
```

### 杂项 函数
```php
echo()
uniqid()
exit()
die()
getenv()
putenv()
memory_get_usage()
memory_get_peak_usage()
version_compare()
zip_open()
Ternary(condition bool, trueVal, falseVal interface{}) interface{}
```

## LICENSE
gofunctools source code is licensed under the [MIT](https://github.com/chenpeng78/gofunctools/blob/master/LICENSE) Licence.
