---
description: Шаблонный движок - важная составляющая движка приветствий и прощаний
---

# Шаблонный движок

{% hint style="warning" %}
Все переменные необходимо писать в фигурных скобках, для соблюдения синтаксиса, например:  
`{member}`
{% endhint %}

## Member

Свойство `member` возвращает упоминание участника и имеет несколько переменных

```javascript
member
member.name
member.id
member.createdAt
```

Для модуля прощаний есть дополнительные переменные

```javascript
member.highestRole
member.roles
member.joinedAt
```

## Guild

Свойство `guild` вернёт название сервера, точно так-же как и `guild.name`

```javascript
guild
guild.name
guild.id
guild.owner                 //Вернёт упоминание владельца
guild.owner.id              //Вернёт айди владельца
guild.owner.name            //Вернёт имя владельца
guild.createdAt
guild.memberCount
```



## 



