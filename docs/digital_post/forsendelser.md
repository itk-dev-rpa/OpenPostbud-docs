---
title: Forsendelser
layout: page
nav_order: 1
parent: Digital Post
---

# Forsendelser

## Overblik

På denne side kan du se et overblik over alle forsendelser,
der er foretaget i OpenPostbud. Her kan du også oprette en
ny forsendelse.

![Forsendelser]({{ "assets/images/digital_post/forsendelser/forsendelser_overblik.png" | relative_url }})

## Forsendelse detaljer

Hvis du trykker på en forsendelse i overblikket kommer du til forsendelsens
detaljeside, hvor du kan se oplysninger om forsendelsen samt alle brevene
i forsendelsen.

Her har du også mulighed for at afbryde en forsendelse. Det er dog ikke muligt at fortryde
breve, som allerede er afsendt. OpenPostbud har en indbygget ventetid, før breve i en forsendelse
bliver afsendt. Den er som udgangspunkt 5 minutter, men kan ændres af systemadministratoren.

Du kan også downloade den brevskabelon, som er blevet brugt til forsendelsen. Det er
**ikke** muligt at se de individuelle breve eller deres flettedata.

Du kan også downloade oversigten over breve som en csv-fil ved at trykke 'Download liste'.
Og du kan søge i oversigten med søgefeltet. Søgefeltet søger i alle kolonner, så søger
du for eksempel på 'Fejlet', kan du se alle fejlede breve. Af sikkerhedshensyn er
de sidste 4 cifre i cpr-numre sløret, så du kan derfor ikke søge på fulde cpr-numre.

![Forsendelsesdetaljer]({{ "assets/images/digital_post/forsendelser/forsendelse_detaljer.png" | relative_url }})

### Brevstatus

I tabellen over breve, kan du se status på alle breve i forsendelsen.

Det fremgår også hvornår statussen sidst er blevet opdateret. Det er kun muligt
at se tidspunktet for sidste statusopdatering.

Breve kan have følgende statusser:

| Status    | Beskrivelse                                                                             |
| --------- | --------------------------------------------------------------------------------------- |
| Afventer  | Brevet er i kø til at blive afsendt.                                                    |
| Behandles | Brevet er ved at blive afsendt.                                                         |
| Afsendt   | Brevet er leveret til Kombits systemer.                                                 |
| Leveret   | En kvittering for levering til modtager er modtaget fra Kombit                          |
| Fejlet    | En fejl opstod under afsendelse af brevet. Dette er oftest uddybet i 'Besked'-kolonnen. |
| Afbrudt   | Afsendelse er blevet manuelt afbrudt af en bruger.                                      |
