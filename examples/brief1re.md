---
fontsize: 11pt
address:
    - An Max Mustermann
    - Fake Street 123
    - 12345 Berlin
    - Deutschland
backaddress:
    - Erika Mustermann
    - Musterhaus 2
    - 99999 Musterstadt
fromaddress:
    - Musterhaus 2
    - 99999 Musterstadt
fromname: Erika Musterfrau
fromemail: example@example.de
invoice: XXX0001
opening: Sehr geehrte Damen und Herren,
closing: Mit freundlichen Grüßen
encl: Wichtige Dokumente
header-includes: |
        \usepackage{longtable}
        \usepackage{array}
        \usepackage{booktabs}
        \chead{\normalfont \sffamily Bankverbindung: IBAN DE84 4756 5746 8474 4755 87 $\cdot$ BIC BGKHDEFG055\\Steuernummer: 75/246/38746}
        \cfoot{}
---
\thispagestyle{scrheadings}
hiermit stelle ich Ihnen die Durchführung der weiter unten aufgelisteten Tätigkeiten in Rechnung.

-------------------------------------------------------------------------
Tätigkeiten                               Datum       Kosten (ohne MwSt.)
----------------------------------------- ---------- --------------------
T1                                        27.10.2020                200 €

T23                                       20.07.2020                 50 €
-------------------------------------------------------------------------


----------------- ----------
Summe ohne MwSt.    250,00 €
19 % MwSt.           47,50 €
----------------- ----------
Rechnungsbetrag     297,50 €
----------------------------

Ich bitte Sie, den Rechnungsbetrag auf das im Briefkopf aufgeführte Konto zu überweisen.

