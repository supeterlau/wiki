### 2020-08-26

Elixir IEx 多行
  
  (unless Integer.is_odd(2) do
    IO.puts "DONE"
  end)

  https://itnext.io/a-collection-of-tips-for-elixirs-interactive-shell-iex-bff5e177405b A Collection of Tips for Elixir’s Interactive Shell (IEx) | by モハマド Meraj モラー | ITNEXT

### 2020-08-25

MySQL row size max : 65,535 bytes
  所有 column 总大小

  解决方法
    1. 存在外部
    2. 更换存储引擎 Antelope to Barracuda

### 2020-08-22

vim jump to right side 
  brace
  square bracket
  parenthesis
  key: %
  https://stackoverflow.com/questions/13174735/move-to-next-open-or-closing-parenthesis-in-vim
   https://vim.fandom.com/wiki/Moving_to_matching_braces

erlang erl exit: q() ( init.stop() )

### 2020-08-14

https://unix.stackexchange.com/questions/137366/stdout-is-empty

    2>error.log

sed -e 's/\/home\/lxy\//$HOME\//' cargo.log

### 2020-08-09

https://love2dev.com/blog/whats-the-difference-between-encodeuri-and-encodeuricomponent



zip backup.zip 1.jpg 2.jpg

zip -r backup.zip /data

unzip test.zip -d /root/ 默认将文件解压到当前目录

### 2020-08-07

三贴近就是指，贴近实际、贴近生活、贴近群众。这是十六大以来，以胡锦涛同志为总书记的党中央提出的一项重要要求。遵循这一要求，宣传思想战线把“三贴近”作为改进和加强自身工作的一条重要指导原则。贴近实际、贴近生活、贴近群众，是作为党和人民喉舌的新闻媒体从事新闻报道过程中必须遵循的原则之一

http://www.tilaile.com/index.php/question/14008 ping命令是属于tcp/ip的哪一层？ 数据链路层 表示层 网络层 应用层_题来了

网络层包括：IP(Internet Protocol）协议、ICMP(Internet Control Message

Protocol) 控制报文协议、ARP(Address Resolution

Protocol）地址转换协议、RARP(Reverse ARP)反向地址转换协议。

IP是网络层的核心，通过路由选择将下一条IP封装后交给接口层。IP数据报是无连接服务。

ICMP是网络层的补充，可以回送报文。用来检测网络是否通畅。 Ping命令就是发送ICMP的echo包，通过回送的echo relay进行网络测试。

### 2020-08-05

https://linuxize.com/post/how-to-remove-symbolic-links-in-linux/


grep -rin --exclude-dir=node_modules todo .


### 2020-08-03

JS 的 switch 分支作用域内不能声明同名变量


https://semver.org/
MAJOR version when you make incompatible API changes,
MINOR version when you add functionality in a backwards compatible manner, and
PATCH version when you make backwards compatible bug fixes.



glob-pattern
    **/*
    **/*.*
    http://www.globtester.com/
    https://www.malikbrowne.com/blog/a-beginners-guide-glob-patterns
    https://stackoverflow.com/questions/21689334/gulp-globbing-how-to-watch-everything-below-directory

GitHub found 7 vulnerabilities ??? quick solve

VSCode 合并多行为一行 Ctrl+J (macOS)
VSCode 开关内置终端 CMD+J (macOS)


http -F(--follow) url
https://httpie.org/docs#follow-location


Host permissions and content script matching are based on a set of URLs defined by match patterns
The special pattern `<all_urls>` matches any URL that starts with a permitted scheme https://developer.chrome.com/extensions/match_patterns


Tree Shaking 摇树优化，是一种在打包时去除没用到的代码的优化手段，谷歌有一篇教程可以了解下: Reduce JavaScript Payloads with Tree Shaking


JS字符串查找（6种方法） http://c.biancheng.net/view/5581.html
  charAt()	返回字符串中的第 n 个字符
  charCodeAt()	返回字符串中的第 n 个字符的代码
  indexOf()	检索字符串
  lastIndexOf()	从后向前检索一个字符串
  match()	找到一个或多个正则表达式的匹配
  search()	检索与正则表达式相匹配的子串

请使用 git clone https://gitclone.com/github.com/xxx/yyy.git 加速 clone，或使用 cgit clone https://github.com/xxx/yyy.git


.gitkeep 文件 用于提交空文件


git clone --depth=1 git-url


Javascript 闭包陷阱

    for(var i=0;i<10;i++){
      setTimeout(function(){
        console.log(i);
      },10);
    }