---
title: Ny Forsendelse
layout: page
nav_order: 2
parent: NemSMS
---

# Ny forsendelse

På denne side kan du oprette en ny NemSMS forsendelse.

Først skal du angive et navn og beskrivelse til forsendelsen.
Disse er kun til intern brug i OpenPostbud og bliver ikke
vist til modtagerne af NemSMS-forsendelsen.

Dernæst skal du angive beskeden, som skal sendes via NemSMS.
Denne besked kan maks være 160 karakterer lang.
Da sms som udgangspunkt ikke er en sikker kanal, bør din besked
ikke indeholde nogen fortrolige oplysninger.

Til sidst skal du uploade en liste med cpr-numre på modtagerne
af NemSMS'erne. Dette skal blot være en tekstfil med alle cpr-numrene
på hver sin linje. Ingen overskrifter eller lignende.

Herefter kan du trykke 'Indsend', hvorefter NemSMS'erne sættes i kø til afsendelse.
Du vil automatisk blive videresendt til forsendelsens detalje-side. Læs mere om
det [her]({{ "/docs/nemsms/forsendelser#forsendelse-detaljer" | relative_url}})

![Ny NemSMS forsendelse]({{ "/assets/images/nemsms/ny_forsendelse.png" | relative_url }})
