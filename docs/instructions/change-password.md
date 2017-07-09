# Изменение пароля

Если вы забыли пароль, можете изменить его, заполнив эту форму.

<div class="form-style-8">
  <form method="POST" >
    <input type="text"      oninput="isValidFormChangePassword()" id="login" placeholder="Логин" />
    <input type="text"      oninput="isValidFormChangePassword()" id="email" placeholder="Email" />
    <input type="password"  oninput="isValidFormChangePassword()" id="pass1" placeholder="Новый пароль" />
    <input type="password"  oninput="isValidFormChangePassword()" id="pass2" placeholder="Новый пароль ещё раз" />
    <label for="pass2" id="pass2label"></label>
    <input type="button" value="Изменить пароль" onclick="setNewPassword()" />
  </form>
</div>

> [info]
> Если при регистрации аккаунта в игре Вам не предлагалось ввести адрес электронной почты (e-mail) - обратитесь к администрации в [Discord-чате](https://discord.gg/aTza5Hk).
