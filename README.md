<!-- MIT License

Copyright (c) 2024 TychoJ

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE. -->

# Inhoudsopgaven

- <h3><a href="#inleiding">Inleiding</a>  </h3>
- <h3><a href="#structuur">Structuur</a>  </h3>
- <h3><a href="#latex">Latex</a>  </h3>
- <h3><a href="#issues">Issues</a>  </h3>
- <h3><a href="#mergeRequests">Merge requests</a>  </h3>

# Inleiding

<div id="Inleiding"></div>
Dit latex template kan gebruikt worden voor het schrijven van verslagen voor de minor Teaching Technology and Science en de Educatieve minor van de Hogeschool van Amsterdam (HvA).

# Structuur

<div id="structuur"></div>
De verschillende bestanden en directories die in dit template worden gebruikt hebben verschillende doelen. De bestanden structuur wordt <a href="#fileStructure">hier</a> getoond.

<div id="fileStructure">
<pre>
├── LICENSE  
├── README.md  
├── hvaFoo.sty  
├── hvaTemplate.sty  
├── references.bib  
├── img/  
├── Logos/  
│   ├── HvA_compact_zwart_RGB.pdf  
│   └── HvA-Lerarenopleidingen-zwart-RGB.pdf  
└── report.tex
</pre>
<p style="text-align:center;">Bestanden structuur van de TTS-latexTemplate</p>
</div>

### De belangrijkste bestanden

- `hvaFoo.sty`  
Implementeert twee commando's, een commando om een lesplan formulier in te vullen en een commando om een observatie  lesuitvoer in te vullen.
- `hvaTemplate.sty`  
Hierin staan een aantal standaard latex packages en wordt de pagina indeling mee opgezet. Daarnaast zorgt dit bestand er voor dat er een titel pagina/voorblad kan worden gegenereerd in een HvA stijl en kan er voor worden gekozen uit een tweetal copyrights. 
- `references.bib`  
Hierin komen alle bibtex referenties te staan waarnaar wordt verwezen.
- `report.tex`  
Hierin wordt het verslag geschreven. Om het latex project in meerdere bestanden op te kunnen delen kan er bijvoorbeeld gebruik worden gemaakt van `\input{<relative path to tex file>}`.

### De belangrijkste directories

- `img/`  
Bevat alle afbeeldingen die in het latex project worden gebruikt.
- `Logos/`  
Bevat alle afbeeldingen/logo's die door `hvaTemplate.sty` worden gebruikt.

# Latex

<div id="latex"></div>
Latex kan gebruikt worden voor het schrijven van verslagen en genereert op basis van de `.tex` bestanden een pdf. Het zogenaamd compileren van een latex bestand kan lokaal (op de eigen computer) gedaan worden als mede in de cloud.

## Latex in de cloud compileren

De meest gebruiksvriendelijke manier om latex projecten te compileren voor een nieuwe gebruiker is door gebruik te maken van <a href="https://www.overleaf.com">Overleaf</a>. Om Overleaf te kunnen gebruiken moet je een gratis account aanmaken. Na het aanmaken van een nieuw project kunnen de bestanden van dit repository naar het nieuwe project worden geüpload en kan er verder worden gewerkt in de Overleaf omgeving.

## Latex lokaal compileren

Het compileren van grotere projecten in Overleaf kost erg veel tijd en kan een reden zijn om een latex project lokaal te willen compileren. Er bestaan een aantal editors die hiervoor gebruikt kunnen worden.
- <a href="https://www.texstudio.org">texstudio</a>
- <a hfef="https://code.visualstudio.com">vscode</a> met de <a href="https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop">latex-workshop</a> extensie

De eisen voor de installatie is terug te vinden via de links hierboven en zal hier niet verder worden toegelicht.

# Issues

<div id="issues"></div>
Indien er een bug of fout is gevonden in dit repository wordt er vriendelijk verzocht hier een issue voor aan te maken. Het is fijn als er in een issue wordt beschreven wat het probleem is en hoe het probleem gereproduceerd kan worden.

Wanneer er een feature mist kan ook hiervoor een issue worden aangemaakt. Beschrijf in een dergelijk issue wat de gewenste feature is en waarom die nodig is.

# Merge requests

<div id="mergeRequests"></div>
Verbeteringen op deze template worden natuurlijk erg gewaardeerd. Als je een verbetering wilt maken is het de bedoeling dat je eerst een issue aanmaakt met daarin beschreven wat je beoogde verbetering inhoud waarna je bij een merge request naar de start issue kunt verwijzen. Op deze manier blijft het overzichtelijk om de veranderingen bij te houden.

Voordat een merge request wordt geaccepteerd zal er worden gekeken naar de aanpassingen van de merge request. Het is de bedoeling dat een merge request een enkel issue oplost. Als een merge request meerdere issues tegelijkertijd oplost zal deze worden geweigerd en moet de merge request worden opgesplitst in meerdere losse merge requests.