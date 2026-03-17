---
title: Skabeloner
layout: page
nav_order: 4
parent: Digital Post
---

# Skabeloner

Skabeloner i OpenPostbud laves i Word som .docx-filer.

Der benyttes Jinja2 syntaks. Hvis du ikke ved hvad det betyder, er det ikke vigtigt.

## Simple flettefelter

Når man opbygger en skabelon, så vil man oftest kunne nøjes med simple flettefelter,
hvor en værdi indsættes i stedet for en pladsholder.

Pladsholdere defineres ved hjælp af dobbelte "tuborgklammer" (akkolader), således:
{% raw %}
`{{ Pladsholder-navn }}`
{% endraw %}

**Bemærk** mellemrummene mellem tuborgklammerne og pladsholderens navn.

**Tip** tuborgklammer findes på talknapperne 7 og 0.
Man skal altså trykke Ctrl+Alt+7 eller Ctrl+Alt+0.

**Tip** undgå at bruge mellemrum og specialtegn i pladsholdernavne. Bindestreg er fint.

## Hvis-klausuler

Det er også muligt at have afsnit i sin skabelon, som kun bliver vist i det endelige
brev, hvis en kolonne i ens flettedata har en bestemt værdi. Dette gøres således:

{% raw %}

```text
{%p if pladsholder == "Sandt" %}
Dette er en brødtekst.
{%p endif %}
```

{% endraw %}

I dette eksempel vil teksten "Dette er en brødtekst." kun fremgå af brevet, hvis pladsholderens
værdi er "Sandt". Hvis ikke vil både klausulen og brødteksten blive fjernet.
