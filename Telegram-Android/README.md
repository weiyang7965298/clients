# [Telegram-Android](https://github.com/DrKLO/Telegram) patch
> [Telegram-Android](https://github.com/DrKLO/Telegram) patched by [NebulaChat](https://nebula.chat)

## Install

- Get *[Telegram-Android](https://github.com/DrKLO/Telegram)* source code

- patch

- build, see [build Telegram-Android](https://github.com/DrKLO/Telegram/blob/master/README.md), and google

## Replace your server and port in ConnectionManager.cpp.diff file

**Default connect to NebulaChat test server.**

If you want to connect to your own server, you can modify the following code:

```
Telegram-Android/ConnectionManager.cpp.diff
L10

+    std::string _nebulaChatServer("47.100.25.99");

```
