## Getting Started
 Install a Ruby+Devkit version from RubyInstaller Downloads (MSYS2 and MINGW development tool chain.)

```
gem install jekyll bundler
bundle install
bundle exec jekyll serve
```

```
# 读取微信书架内容
let shelf_arr = []; // 存储链接
let shelf_book = document.getElementsByClassName("shelfBook"); // 书籍
for (i = 0; i < shelf_book.length; i++) {
  shelf_arr.push(shelf_book[i].href.replace("reader", "bookDetail"));
}
console.log(shelf_arr);
————————————————
版权声明：本文为CSDN博主「差不多的张三」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/qq_45196785/article/details/124767864
```