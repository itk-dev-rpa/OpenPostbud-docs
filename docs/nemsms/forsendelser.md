---
title: Forsendelser
layout: page
nav_order: 1
parent: NemSMS
---

# Forsendelser

## Overblik

På denne side kan du se et overblik over alle forsendelser,
der er foretaget i OpenPostbud. Her kan du også oprette en
ny forsendelse.

![Overblik]({{ "/assets/images/nemsms/overblik.png" | relative_url }})

## Forsendelse detaljer

Hvis du trykker på en forsendelse i overblikket kommer du til forsendelsens
detaljeside, hvor du kan se oplysninger om forsendelsen samt alle beskeder
i forsendelsen.

Her har du også mulighed for at afbryde en forsendelse. Det er dog ikke muligt at fortryde
beskeder, som allerede er afsendt. OpenPostbud har en indbygget ventetid, før beskeder i en forsendelse
bliver afsendt. Den er som udgangspunkt 5 minutter, men kan ændres af systemadministratoren.

Du kan også downloade oversigten over beskeder som en csv-fil ved at trykke 'Download liste'.
Og du kan søge i oversigten med søgefeltet. Søgefeltet søger i alle kolonner, så søger
du for eksempel på 'Fejlet', kan du se alle fejlede beskeder. Af sikkerhedshensyn er
de sidste 4 cifre i cpr-numre sløret, så du kan derfor ikke søge på fulde cpr-numre.

![Detaljer]({{ "/assets/images/nemsms/detaljer.png" | relative_url }})

### Beskedstatus

I tabellen over beskeder, kan du se status på alle beskeder i forsendelsen.

Det fremgår også hvornår statussen sidst er blevet opdateret. Det er kun muligt
at se tidspunktet for sidste statusopdatering.

Beskeder kan have følgende statusser:

| Status    | Beskrivelse                                                                               |
| --------- | ----------------------------------------------------------------------------------------- |
| Afventer  | Beskeden er i kø til at blive afsendt.                                                    |
| Behandles | Beskeden er ved at blive afsendt.                                                         |
| Afsendt   | Beskeden er leveret til Kombits systemer.                                                 |
| Leveret   | En kvittering for levering til modtager er modtaget fra Kombit                            |
| Fejlet    | En fejl opstod under afsendelse af beskeden. Dette er oftest uddybet i 'Besked'-kolonnen. |
| Afbrudt   | Afsendelse er blevet manuelt afbrudt af en bruger.                                        |
