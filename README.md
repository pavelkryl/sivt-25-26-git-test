# Iniciální setup

Vytvořte vlastní **veřejný** GitHub repozitář. Bude jednodušší, když při vytváření zaškrtnete automatické přidání souboru `README.md`

Vyklonujte si ho k sobě na disk do složky:

Vaším cílem je splnit následující kroky a vytvořit ucelenou historii změn ve vašem repozitáři. Po každém provedeném kroku je vhodné ověřit svůj stav pomocí git status a pak nahrát změny na server.

## 1. krok: Tvorba základních souborů

Vytvořte nový soubor s názvem `seznam_studentu.txt`.

Do tohoto souboru zapište jméno a e-mail třech studentů (každé na nový řádek).

Vytvořte druhý soubor s názvem `main.py`. Do něj zkopírujte následující kód (nebo jakýkoli jednoduchý Python kód):

```python
def pozdrav(jmeno):
    return f"Ahoj, {jmeno}! Toto je verze 1.0."

if __name__ == "__main__":
    print(pozdrav("Svět Gitu"))
```

Vytvořte commit se zprávou: "První nástřel: Seznam studentů a hlavní skript".

Nahrajte změny na github.

## 2. krok: Modifikace a vytvoření pomocného souboru

Modifikujte soubor `main.py`: Změňte text ve funkci pozdrav na 

`"Ahoj, {jmeno}! Toto je verze 1.1 - upraveno."`

Vytvořte nový adresář s názvem `data`.

Uvnitř adresáře `data` vytvořte soubor `konfigurace.txt` a zapište do něj jeden řádek: 
```
DEBUG=False.
```

Vytvořte commit se zprávou: "Úprava hlavního skriptu na v1.1 a přidání složky s konfigurací".

Nahrajte změny na github.

## 3. krok: simulace práce kolegy a stažení změn

Přejděte do webového rozhraní vašeho GitHub repozitáře (v prohlížeči, ne lokálně).

Přímo ve webovém rozhraní najděte soubor `README.md` a klikněte na "Edit".

Na konec souboru README.md přidejte nový řádek, např.: "Tento repozitář byl upraven přímo na GitHubu."

Commit proveďte přímo ve webovém rozhraní.

Vraťte se do lokálního repozitáře (do terminálu).

Stáhněte si změny z remote repozitáře.

## 4. krok: odstranění souborů a konečná úprava

Rozhodli jste se, že soubor `seznam_studentu.txt` už není potřeba. Odstraňte soubor z repozitáře a pracovního adresáře (nápověda: na to je příkaz `git rm`).

Modifikujte soubor `main.py`: Přidejte komentář na začátek souboru, např.: Python

Vytvořte commit se zprávou: "Odstranění seznam_studentu.txt a finální úprava hlavního skriptu.".

Nahrajte změny na github.

# Konec úlohy

Nyní mi do google classroom do komentáře našeho testu pošlete odkaz na vaše repo (URL z prohlížeče stačí).

🏁 Dokončení cvičení
Posledním krokem je poslání odkazu na váš repozitář, abych mohl/a zkontrolovat historii commitů a finální stav souborů.
