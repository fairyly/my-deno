# my-deno

>ry----deno: 下一代Node--Deno

>Deno 也是一个服务器运行时，但是支持多种语言，可以直接运行 JavaScript、TypeScript 和 WebAssembly 程序。
它内置了 V8 引擎，用来解释 JavaScript。同时，也内置了 tsc 引擎，解释 TypeScript。
它使用 Rust 语言开发，由于 Rust 原生支持 WebAssembly，所以它也能直接运行 WebAssembly。
它的异步操作不使用 libuv 这个库，而是使用 Rust 语言的 Tokio 库，来实现事件循环（event loop）。

## install

- Windows安装: 使用 `curl/powershell` 一直下载失败，最后下载 编译好的 [exe 文件 deno-x86_64-pc-windows-msvc.zip](https://github.com/denoland/deno/releases)
``` 
把压缩文件里的 deno.exe 放到一个路径下，添加到环境变量中
```

- 其他平台

```
Using Shell (macOS, Linux):

curl -fsSL https://deno.land/x/install/install.sh | sh


Using PowerShell (Windows):

iwr https://deno.land/x/install/install.ps1 -useb | iex


Using Homebrew (macOS):

brew install deno

Using Chocolatey (Windows):

choco install deno

Using Scoop (Windows):

scoop install deno
```

- https://github.com/denoland/deno_install

>Deno 的安装可以参考官网首页，但是你可以直接去 GitHub 仓库的[发布页](https://github.com/denoland/deno/releases)，下载编译好的可执行文件


## 参考

- [deno.land](https://deno.land/)
- [docs](https://doc.deno.land/https/github.com/denoland/deno/releases/latest/download/lib.deno.d.ts)

- [deno 社区](https://denocn.org/)

- cnode: https://cnodejs.org/topic/5b0f9ba357137f22415c47b5

- deno github: https://github.com/ry/deno

- [Deno 运行时入门教程：Node.js 的替代品](ruanyifeng.com/blog/2020/01/deno-intro.html)

- [denolib/awesome-deno](https://github.com/denolib/awesome-deno)
- [NMathar/deno-express](https://github.com/NMathar/deno-express)
- [oakserver/oak](https://github.com/oakserver/oak)
