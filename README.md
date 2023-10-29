# basicHTML5
<iframe width="560" height="315" src="https://www.youtube.com/embed/2PS21k6lAD8?si=a5p86Tjb427RV_-_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> - тег для того что бы вставлять ссылки на другие сайты. в этом случае видос на ютубе
<video controls autoplay src=""></video> - тег для видео с контролером и автоплейем
<a href="https://instagram.com" target = "_blank">instagram</a> -ссылка с переходом на другую стр 
<a href="tel: +994- 070- 711 - 54 - 45">tel</a> - ссылка на позвонить
<a href="mailto:n.hasratoav@mail.ru">email</a>


<form action="" method="">
    <label for="login">login</label>
    <input type="text" name="login" placeholder="name">
    <label for="password">password</label>
    <input type="password" name="password" placeholder="password">
    <button type="submit">enter</button>
   </form>

   
<form action="">
    <label for="avatar">avatar</label>
    <input type="file" name="avatar">
    <button type="submit">send</button>
</form>

<input type="file" name="avatar" accept="image/png, image/jpeg">
value = "" - значение по умолчанию

<label for="age">age</label>
<input type="number" name="age" id="" min="" max="" value="" step= "">

<form action="">
        <label for="phone">Choose your phone</label>
        <select name="phone" id="phone">
            <option value="">--Your phone--</option>
            <option value="apple">Apple</option>
            <option value="nokia">Nokia</option>
            <option value="samsung">Samsung</option>

        </select>
</form>

<h2>Chechbox form</h2>
    <form action="">
        <label for="checkbox1">Yes</label>
        <input type="checkbox" name="checkbox1" id="">
    </form>
    <h2>Radio form</h2>
    <form action="">
        <label for="radio1">Yes</label>
        <input type="radio" name="radio1" id="">
        <label for="radio1">No</label>
        <input type="radio" name="radio1" id="">
    </form>
    <h2>Slider Form</h2>
    <form action="">
        <input type="range" name="volume" id="volume">
        <output class="volume-output"></output>
    </form>
    <script>
        const volume = document.querySelector('#volume');
        const output = document.querySelector('.volume-output');

        output.textContent = volume.value;
        volume.addEventListener('input', () =>{
            output.textContent = volume.value;
        })
    </script>