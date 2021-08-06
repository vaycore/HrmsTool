# HrmsTool

hrms加解密工具

## 使用方式

需要 **Java1.8** 环境，执行如下命令启动 `HrmsTool` 工具， `-e` 是加密， `-d` 是解密

```bash
$ java -jar HrmsTool.jar
Usage:
    java -jar HrmsTool.jar -e xxx
    java -jar HrmsTool.jar -d xxx
```

## 使用例子

加密

```bash
$ java -jar HrmsTool.jar -e C:/Windows/win.ini
safe-encode: C~3a~2fWindows~2fwin~2eini
encrypt: VHmj0PAATTP2HJBPAATTPcyRcHb6hPAATTP2HJFPAATTP59XObqwUZaPAATTP2HJBPAATTP6EvXjT
```

解密

```bash
$ java -jar HrmsTool.jar -d VHmj0PAATTP2HJBPAATTPcyRcHb6hPAATTP2HJFPAATTP59XObqwUZaPAATTP2HJBPAATTP6EvXjT
safe-decode: VHmj0PAATTP2HJBPAATTPcyRcHb6hPAATTP2HJFPAATTP59XObqwUZaPAATTP2HJBPAATTP6EvXjT
decrypt: C:/Windows/win.ini
```
