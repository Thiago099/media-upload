# Upload do iphone


Como rodar 

```js

npm install
npm run dev

```


Com esta configuração o próprio iPhone faz a conversão na hora de fazer o upload

```js

<input type="file" accept="video/*, image/*" id="file">
<script>
    file.onchange = event => alert(event.target.files[0].type)
</script>

```