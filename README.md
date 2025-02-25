# Raflost HiDef Prjón

Þetta geymsla inniheldur grein um snjallvædda prjónavél sem verður kynnt á **Raflost 2025**. Greinin fjallar um þróun og útfærslu á sjálfvirkri prjónavél með opnum hugbúnaði og var hluti af verkefni sem var styrkt af **Nýsköpunarsjóði námsmanna sumarið 2024**.

## Innihald
- **`raflost.tex`** – LaTeX skrá með greininni.
- **`references.bib`** – Heimildaskrá.
- **`figs/`** – Myndir sem eru notaðar í greininni.

## Uppsetning og notkun
Til að vinna með skjölin og setja þau upp á staðnum þarftu að hafa **LaTeX uppsett** á vélinni þinni. Þú getur þýtt skjalið með eftirfarandi skipunum:

```bash
pdflatex raflost.tex
biber raflost
pdflatex raflost.tex
pdflatex raflost.tex
```
Þetta tryggir að allar tilvísanir og heimildir séu rétt birtar.

## Um verkefnið
Verkefnið fjallar um þróun snjallvæddrar prjónavélar með sjálfvirkri mynsturgerð. Vinnan byggði á þverfaglegu samstarfi hagnýtrar stærðfræði, tölvunarfræði og fatahönnunar.

## Myndir
Öll myndefni sem notuð eru í greininni eru vistuð í figs/ undirmöppunni.

## Höfundur
Helga Ingimundardóttir, lektor í iðnaðarverkfræði og verkefnastjóri *HiDef textíl* verkefnins. 

### Sumarstarfsmenn NSN 2024
- Guðrún Ísafold Hilmarsdóttir – Fatahönnun og hönnunarferli
- Snæfríður Ebba Ásgeirsdóttir – Hugbúnaðarhönnun og mynsturgerð
- Elías Lúðvíksson – Vélbúnaðaruppfærslur og kerfisþróun

## Leyfi
Allur kóði og efni í þessu safni er gefið út undir [MIT-leyfi](LICENSE), nema annað sé tekið fram.