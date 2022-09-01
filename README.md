# frida-trace
this is frida trace assemble and  register change tools

介绍
https://bbs.pediy.com/thread-273501.htm

npm install编译完跑_agent.js

clone下来后npm install   然后修改straceInject.js 里的 soName 和 要hook的函数和方法大小 然后npm run build 生成新的_agent.js 最后直接Frida -I 跑就行了 就跟你平时跑Frida脚本一样
