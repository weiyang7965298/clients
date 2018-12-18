# [Telegram-FOSS](https://github.com/Telegram-FOSS-Team/Telegram-FOSS) patch
> [Telegram-FOSS](https://github.com/Telegram-FOSS-Team/Telegram-FOSS) patched by [NebulaChat](https://nebula.chat)

## Install

- Get *[Telegram-FOSS](https://github.com/Telegram-FOSS-Team/Telegram-FOSS)* source code

- patch

- build, see [build Telegram-FOSS](https://github.com/Telegram-FOSS-Team/Telegram-FOSS/blob/master/README.md), and google

## Replace your server and port in ConnectionManager.cpp file

**Default connect to NebulaChat test server.**

If you want to connect to your own server, you can modify the following code:

```
Telegram-FOSS/ConnectionManager.cpp.diff
L11

+    std::string _nebulaChatServer("47.100.25.99");

```
