```js

client.on('messageCreate', message => {
  if (message.content.startsWith('رابط')) {
    return message.reply('https://discord.gg/ane')
  }
});

//تقدر تنسخ الكود و تكتبه تاني تحت لو عاوز تضيف رد كمان 
```
```# Description:  Reply message / رد تلقائي ```


```js

client.on('messageCreate', message => {
  if (message.content.startsWith('خط')) {
    return message.reply('')
  }
});

//تقدر تنسخ الكود و تكتبه تاني تحت لو عاوز تضيف رد كمان 
```
```# Description:  Reply message / رد تلقائي ```
