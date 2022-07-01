# django_test_endevel

Připravte blog s editovatelnou správou obsahu v Pythonu (Django).

Webové stránky blogu se budou skládat v podstatě ze 3 typových stránek:

    homepage neboli stránka s výpisem článků (zobrazit poslední 3 blogy)

    detail článku

    stránka s výsledky vyhledávání podle tagů

        pokud kliknu na nějaký tag, tak by se měly zobrazit všechny články s tímto tagem


V administraci je nutné umět:

    vytvořit novou blog page

    vytvořit nové tagy

    přiřadit tagy k blogům

Článek by měl mít tyto fieldy:

    Title

    Obsah

    možnost přidání tagů

    full image pro zobrazení v detailu

    image thumb pro zobrazení v listu (backend bude thumb automaticky vytvářet z full image)


Zpracování (2 varianty)

    JUNIOR použijte grafickou šablonu podle vlastního výběru a udělejte fungující web

    MEDIOR + SENIOR vypublikujte API (REST nebo GraphQL) pro frontend, tak aby byl frontend schopen blog zobrazit

Hodnocení:

    1 bod - Fungující aplikační kód

    1 bod - Základní optimalizace kódu

    1 bod - Připravte Docker compose (db, app, atd.) pro rozběhnutí projektu. 

    1 bod - Připravte alespoň několik fixtures pro snadné nalití testovacích dat do DB.

    1 bod - Napište dostatek unit testů pokrývající váš kód

    1 bod - Připravte pipeline (Github, Gitlab, Bitbucket) kde se budou spouštět testy



Kritéria pro přijetí:

Senior - 5 bodů ze 6

Medior - 3 body ze 6
