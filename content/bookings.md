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

<form>
    <fieldset>
        <legend>Book a standard tattoo session</legend>
        <label for="name">Name</label>
        <input name="name" type="text" required/>
        <label for="pronouns">Pronouns</label>
        <input name="pronouns" type="text"/>
        <label for="email">Email</label>
        <input name="email" type="email" required/>
        <div class="checkbox">
            <input name="over18" type="checkbox"/>
            <label for="over18">Are you over 18?</label>
        </div>
        <div class="checkbox">
            <input name="firsttattoo" type="checkbox"/>
            <label for="firsttattoo">Have you been tattooed before?</label>
        </div>
        <label for="location">Where do you live?</label>
        <input name="location" type="text" required/>
        <label for="desc">Description / placement / size</label>
        <textarea name="desc" required></textarea>
        <button type="submit">Send request</button>
    </fieldset>
</form>

## Liminal Marks

<form>
    <fieldset>
        <legend>Book a liminal tattoo session</legend>
        <label for="name">Name</label>
        <input name="name" type="text" required/>
        <label for="pronouns">Pronouns</label>
        <input name="pronouns" type="text"/>
        <label for="email">Email</label>
        <input name="email" type="email" required/>
        <div class="checkbox">
            <input name="over18" type="checkbox"/>
            <label for="over18">Are you over 18?</label>
        </div>
        <div class="checkbox">
            <input name="firsttattoo" type="checkbox"/>
            <label for="firsttattoo">Have you been tattooed before?</label>
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
        <button type="submit">Send request</button>
    </fieldset>
</form>

## Shamanic Healing

<form>
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
        <button type="submit">Send request</button>
    </fieldset>
</form>