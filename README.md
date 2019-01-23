## Negotiation
The extension shows info about cause of negotiations in tender.
## Overview
The fields introduced by this extension are:
- `tender/cause` - The cause of negotiations. See Article 35 of the Law of Ukraine "On Public Procurement". 
Required for openprocurement.limited. It should be string value.
- `tender/causeDescription` - The reasoning behind usage of negotiations. 
Required for openprocurement.limited. It should be string value.
# Example
The following extract illustrates these properties in use within the `tender` block.
```
{
    "tender": {
        "id": "d014500a9769491a81f3f1cecc1004f3",
        "cause": "noCompetition",
        "causeDescription": "Умова застосування переговорної процедури закупівлі відповідно до п.2 статті 35 Закону України \"Про публічні закупівлі\"\r\nВідсутність конкуренції (у тому числі з технічних причин) щодо розподілу та передачі електричної енергії (єдиний можливий постачальник – природній монополіст ПрАТ «Волиньобленерго») на відповідному ринку, внаслідок чого договір про закупівлю може бути укладено лише з одним постачальником, за відсутності при цьому альтернативи.\r\n\r\n- Копія ліцензії на передачу електроенергії місцевими електричними мережами та копія ліцензії на постачання за регульованим тарифом\r\n- копія Статуту ПрАТ «Волиньобленерго»\r\n- копія витягу з ЄДРПОУ\r\n- копія свідоцтва про державну реєстрацію юридичної особи.\r\n\r\n\r\n",
    }
}
```
