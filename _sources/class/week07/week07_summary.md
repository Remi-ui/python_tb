(page_topic7)=
Week 7
=======================

## Benodigdheden
- [De dataset](https://github.com/Remi-ui/python_tb/releases/download/Electricity_dataset/Electricity.zip)
- [Het voorbeeld](https://remi-ui.github.io/python_tb/class/week07/energie_nederland.html)
- [Overige bestanden](https://github.com/Remi-ui/python_tb/releases/download/Overige_bestanden/geo_files.zip). Deze bestanden heeft het voorbeeld nodig voor de visualisaties.

## De opdracht
Tijdens deze eindopdracht maak je een analyse van het elektriciteitsverbruik in Nederland.

### Omschrijving
Maak met behulp van het bovenstaande dataset een analyse van het electriciteitsverbruik in Nederland. Stel een Google Colab document op waarin je een aantal zelf gemaakte figuren laat zien en beschrijf de resultaten. Analyseer vervolgens de resultaten en breng op basis van de resultaten een advies uit aan het ministerie van Economische Zaken en Klimaat. De figuren, beschrijving en analyse doe je in een Google Colaborate document. Hoe je kunt schrijven in een Google Colab document kun je [hier](https://colab.research.google.com/notebooks/markdown_guide.ipynb) vinden. Dit is je kans om je Python skills te laten zien!

Let er op dat om het voorbeeld werkende te krijgen, je de [de dataset](https://github.com/Remi-ui/python_tb/releases/download/Electricity_dataset/Electricity.zip) uitgepakt (want het is een .zip bestand) in je drive moet plaatsen. Je plaats dus de folder genaamd "Electricity" in je Google Drive. Tevens moet je de [overige bestanden](https://github.com/Remi-ui/python_tb/releases/download/Overige_bestanden/geo_files.zip) downloaden, uitpakken (want het is een .zip bestand), en in je Drive moet plaatsen. Verander hierbij de folder naam (geo_files) niet.

Verder krijg je bij het uitvoeren van het voorbeeld waarschijnlijk errors gerelateerd aan het niet bestaan van bepaalde mappen/bestanden. Dit komt doordat de mappenstructuur binnen jouw Google Drive waarschijnlijk anders is dan de aangenomen mappenstructuur in het voorbeeld. Hoe je hiermee om kunt gaan kun je [hier](https://www.youtube.com/watch?v=InZ16tcM9Pc&ab_channel=DataProfessor) vinden.

### Voorwaarden
Je verslag bevat tenminste:
1. 8 Zelf gemaakte figuren, gemaakt met het gegeven dataset.
2. Zelf geschreven code. Je mag het voorbeeld gebruiken als hulpmiddel, maar je mag niet dezelfde figuren gebruiken. Als grotere stukken van je code te vinden zijn op het internet of geschreven is door programma's als ChatGPT, is dit plagiaat. Programma's als ChatGPT en hulpmiddelen als Stackoverflow mogen uiteraard gebruikt worden, echter moet hierbij de bron altijd vermeld worden. Ook hierbij mag het niet gaan om grotere stukken code.
3. Een beschrijving én analyse van elk figuur.
4. Een advies aan het ministerie van Economische Zaken en Klimaat op basis van je analyse.
5. De individuele bijdrage is inzichtelijk gemaakt.

### Hulpmiddelen
```{dropdown} Google Colab verbinden met Google Drive
    :class-container: sd-shadow-lg
    :color: primary

<div class="container youtube">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/6UnCrulz-fE?si=-TcdfuiF0UO79vbA" frameborder="0" allow="accelerometer; autoplay="0"; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```

```{dropdown} Bestanden vanuit Google Drive gebruiken in Google Colab
    :class-container: sd-shadow-lg
    :color: primary
<div class="container youtube">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/VCllZKM7Njk?si=cPtduu1dv0OUzbHZ" frameborder="0" allow="accelerometer; autoplay="0"; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```

```{dropdown} Algemene Google Colab tutorial
    :class-container: sd-shadow-lg
    :color: primary
<div class="container youtube">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/inN8seMm7UI?si=SPtey9bcS7z9vPTi" frameborder="0" allow="accelerometer; autoplay="0"; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```

```{dropdown} Matplotlib tutorial
    :class-container: sd-shadow-lg
    :color: primary
<div class="container youtube">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/OZOOLe2imFo?si=9xNtCcxS0FVnj4ku" frameborder="0" allow="accelerometer; autoplay="0"; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```

```{dropdown} Pandas tutorial
    :class-container: sd-shadow-lg
    :color: primary
<div class="container youtube">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/vmEHCJofslg?si=x3F8iEZt4PSrtD3b" frameborder="0" allow="accelerometer; autoplay="0"; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```

```{dropdown} Python basics in 1 uur
    :class-container: sd-shadow-lg
    :color: primary
<div class="container youtube">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/kqtD5dpn9C8?si=qktt1FBzfntIMSST" frameborder="0" allow="accelerometer; autoplay="0"; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```

```{dropdown} Omgaan met mappenstructuren in Google Colab
    :class-container: sd-shadow-lg
    :color: primary
<div class="container youtube">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/InZ16tcM9Pc?si=mRcsb2D7mcCBd18P" frameborder="0" allow="accelerometer; autoplay="0"; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```


### Inleveren
Lever je verslag in als *ipynb* bestand in via eJournal. Dit betekent dus dat zowel het verslag, als de code aanwezig is in je .ipynb bestand.

### Deadline
De deadline voor deze opdracht is donderdag 13 juni 23.59.

### Samenwerken
Je doet deze opdracht in groepen van 3 of 4.

## Beoordelingscriteria
Bij het beoordelen van de eindopdracht gelden de onderstaande beoordelingscriteria.

### Code (33%)
- De code is leesbaar.
- De code is voorzien van commentaar.
- Het commentaar beschrijft wat de code doet en geeft uitleg over de gezette denkstappen.
- De code is functioneel, waarbij de gezette denkstappen in het commentaar zijn opgenomen.
- De code is zelf geschreven, waarbij hulpmiddelen zijn toegestaan.
- De code is van voldoende niveau.

### Analyse (33%)
- De analyse is passend bij wat er in de figuren te zien is.
- In de analyse wordt de data helder geïnterpreteerd.
- Bij de analyse worden externe bronnen betrokken (in APA-stijl) indien van toepassing.

### Advies (33%)
- Het advies heeft een professionele toon.
- Het advies is relevant voor de ontvanger.
- Het advies is een logisch vervolg op de analyse.
