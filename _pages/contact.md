---
title: Контакты
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Пожалуйста отправьте нам сообщение. Ждем с нетерпением! Ваш "{{site.name}}"</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Имя*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Сообщениe*" required></textarea>    
<input class="btn btn-success" type="submit" value="Отправить">
</form>
