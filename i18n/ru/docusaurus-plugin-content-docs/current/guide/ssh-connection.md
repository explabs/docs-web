---
sidebar_position: 4
---

# Подключение по SSH
>  Secure Shell — «безопасная оболочка». Подключение по SSH выполняется с помощью утилиты ssh.

Чтобы подключиться по SSH выполните команду:  
```
ssh -i <private_key> user@ip
```
`private_key` - приватный ключ или путь до него.  
`user` - имя пользователя к которому необходимо подключиться.  
`ip` - IP устройства, к которому необходимо подключиться.

Пример команды:

### Для Linux
```
ssh -i /home/user/.ssh/id_rsab user@192.168.1.2
```

### Для Windows 

```
ssh -i C:\Users\User\.ssh\id_rsa user@192.168.1.2

```

 
:::info
Более подробно о подключении по SSH можно почитать [здесь](https://hackware.ru/?p=9928)
:::