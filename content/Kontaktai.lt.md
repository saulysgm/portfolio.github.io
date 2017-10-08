+++
date = "2017-03-02T11:59:27-05:00"
title = "Kontaktai"
weight = 40
draft = false

+++

<form method="post" action="#">
    <div class="field half first">
        <label for="name">Vardas</label>
        <input type="text" name="name" id="name" />
    </div>
    <div class="field half">
        <label for="email">El. paštas</label>
        <input type="text" name="email" id="email" />
    </div>
    <div class="field">
        <label for="message">Žinutės vieta</label>
        <textarea name="message" id="message" rows="4"></textarea>
    </div>
    <ul class="actions">
        <li><input type="submit" value="Siųsti" class="special" /></li>
        <li><input type="reset" value="Pradėti iš naujo" /></li>
    </ul>
</form>

{{< socialLinks >}}
