---
layout: default
title: Innføring i moderne frontendteknikker
---

# Innføring i moderne frontendteknikker

## Innhold

1. Innledning.
2. HTML5
3. CSS3
4. SASS/COMPASS
5. RWD/Grid systemer

## Innledning

__HTML/CSS:__ Jeg vil i denne innføringen ta for meg de viktigste endringene innført i HTML5 og CSS3, men også trekke frem eldre endringer som de siste årene har fått utbredt nok støtte i nettlesere til å kunne brukes.

__Sass/Compass/RWD/Grid systemer:__ Jeg vil nevne eksempler på preprosessorer for css og gå dypere i eksempler med Sass. Flere eksempler på Sass rammeverk vil nevnes, men Compass vil brukes for å illustrere bruken av rammeverk. Det vil demonstreres teknikker for å oppnå et responsivt design på et nettsted både med og uten bruk av et gridsystem.

## HTML5

### Doctype

For å fortelle nettleseren at dokumentet er html putter du <code><!doctype html></code> som første linje i koden. Dette skal i html5 være tilstrekkelig informasjon til at netteleseren skal håndtere dokumentet på en fornuftig måte.

### Nye elementer for struktur

- <code>header</code>
- <code>nav</code>
- <code>footer</code>
- <code>article</code>
- <code>aside</code>
- <code>section</code>
- <code>main</code>

[Eksempel på struktur i en nettside](http://arejoh.github.io/fendtek/examples/#/kurs?id=structure--structure)

### Nye verdier for <code>type</code>-attributtet i <code>form</code> elementer

- <code>tel</code>
- <code>url</code>
- <code>email</code>
- <code>number</code>
- <code>range</code>
- <code>color</code>
- <code>datetime</code>
- <code>date</code>
- <code>month</code>
- <code>week</code>
- <code>time</code>

[Eksempel på bruk av nye attributerverdier](http://arejoh.github.io/fendtek/examples/#/kurs?id=form-1--form-1) [Flere eksempler på bruk av nye attributtverdier](http://arejoh.github.io/fendtek/examples/#/?id=form-2--form-2)

### ARIA - Accessible Rich Internet Applications

Det viktigste/mest brukte er role-attributtet som forteller en klient hvilken rolle et element har i applikasjonen.

- banner
- form
- main
- navigation
- search

<aside>
  <div class="resources internal">
    <h3>Interne ressurser</h3>
    <ul class="resources__listings">
      <li class="resources__item"><a href="fendtek/examples">Examples</a></li>
      <li class="resources__item"><a href="fendtek/slides">Slides</a></li>
    </ul>
  </div>
  <div>
    <h3>Eksterne ressurser</h3>
    <ul>
        <li class="resources__item"><a href="http://html5doctor.com/">HTML5 Doctor</a></li>
        <li class="resources__item"><a href="http://caniuse.com/">Can I use _____?</a></li>
        <li class="resources__item"><a href="http://www.w3.org/WAI/intro/aria">Oversikt over WAI-ARIA hos w3c.org</a></li>
    </ul>
  </div>
</aside>
