## helloworld

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    <div id='app'>
        <!-- 双向数据绑定 -->
        <input type="text" v-model="username">
        <p>hello {{username}}</p>
    </div>
</body>
<script src="https://cdn.bootcss.com/vue/2.5.16/vue.js"></script>
<script>
    const vm = new Vue({
        el:'#app',
        data:{
            username:'weixin'
        }
    });
</script>
</html>
```