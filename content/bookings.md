+++
title = "Bookings"
subtitle = ""
type = "page"
layout = "text"
+++

<div class="buttons">
<a class="button" href="#tattoo">Tattoo</a>
<a class="button" href="#liminal-marks">Liminal marks</a>
<a class="button" href="#shamanic-healing">Shamanic healing</a>
</div>

## Tattoo

<form action="https://formsubmit.co/contact@liminalmarks.com" method="POST" enctype="multipart/form-data">
    <fieldset>
        <legend>Book a standard tattoo session</legend>
        <label for="name">Name</label>
        <input name="name" type="text" required/>
        <label for="pronouns">Pronouns</label>
        <input name="pronouns" type="text"/>
        <label for="email">Email</label>
        <input name="email" type="email" required/>
        <div class="checkbox">
            <input name="over18" type="checkbox" value="yes"/>
            <label for="over18">Are you over 18?</label>
        </div>
        <div class="checkbox">
            <input name="tattooed-before" type="checkbox" value="yes"/>
            <label for="tattooed-before">Have you been tattooed before?</label>
        </div>
        <label for="location">Where do you live?</label>
        <input name="location" type="text" required/>
        <label for="desc">Description / placement / size</label>
        <textarea name="desc" required></textarea>
        <label for="attachment">Reference pictures</label>
        <input type="file" name="attachment" accept="image/png, image/jpeg">
        <input type="hidden" name="_subject" value="New message from standard tattoo session form">
        <input type="hidden" name="_next" value="http://localhost:1313/thank-you">
        <button type="submit">Send request</button>
    </fieldset>
</form>

{{< ornament style="1" >}}

## Liminal Marks

<form action="https://formsubmit.co/contact@liminalmarks.com" method="POST">
    <fieldset>
        <legend>Book a liminal tattoo session</legend>
        <label for="name">Name</label>
        <input name="name" type="text" required/>
        <label for="pronouns">Pronouns</label>
        <input name="pronouns" type="text"/>
        <label for="email">Email</label>
        <input name="email" type="email" required/>
        <div class="checkbox">
            <input name="over18" type="checkbox" value="yes"/>
            <label for="over18">Are you over 18?</label>
        </div>
        <div class="checkbox">
            <input name="tattooed-before" type="checkbox" value="yes"/>
            <label for="tattooed-before">Have you been tattooed before?</label>
        </div>
        <label for="background">Who are you ? What’s your background ?</label>
        <textarea name="background" required></textarea>
        <label for="story">What would you want this tattoo to bring you ? What story do you want it to tell ?</label>
        <textarea name="story" required></textarea>
        <label for="intentions">What intentions would you hope to engrave onto your skin with this tattoo ?</label>
        <textarea name="intentions" required></textarea>
        <label for="dreams">What are your dreams ?</label>
        <textarea name="dreams"></textarea>
        <label for="values" required>What’s important in your life ? What values do you bear ?</label>
        <textarea name="values"></textarea>
        <label for="dedication">Are you ready for a process that demands dedication and why is it important to you ?</label>
        <textarea name="dedication" required></textarea>
        <input type="hidden" name="_subject" value="New message from liminal marks session form">
        <input type="hidden" name="_next" value="http://localhost:1313/thank-you">
        <button type="submit">Send request</button>
    </fieldset>
</form>

{{< ornament style="1" >}}

## Shamanic Healing

<form action="https://formsubmit.co/contact@liminalmarks.com" method="POST">
    <fieldset>
        <legend>Book a shamanic healing session</legend>
        <label for="name">Name</label>
        <input name="name" type="text" required/>
        <label for="pronouns">Pronouns</label>
        <input name="pronouns" type="text"/>
        <label for="email">Email</label>
        <input name="email" type="email" required/>
        <label for="why">Why do think you need a spiritual healing ?</label>
        <textarea name="why" required></textarea>
        <label for="symptoms">What kind of symptoms do you present ?</label>
        <textarea name="symptoms" required></textarea>
        <input type="hidden" name="_subject" value="New message from shamanic healing session form">
        <input type="hidden" name="_next" value="http://localhost:1313/thank-you">
        <button type="submit">Send request</button>
    </fieldset>
</form>