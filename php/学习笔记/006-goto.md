# goto语句

goto 语句可以用来跳转到程序中的另一个位置。  

目标位置只能位于同一文件和作用域  

示例：
```php
for ($i = 0; $i < 10; $i++) {
  if ($i == 3) {
    goto a;
  }
  echo $i;
}
a:
echo "跳出循环";

// 012跳出循环
```