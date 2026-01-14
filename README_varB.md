# Test z GITu – Varianta B (Python)

## Iniciální setup

Vytvořte vlastní veřejný GitHub repozitář s názvem ve formátu `git-python-test-vaseprijmeni`. Při vytváření zaškrtněte automatické přidání souboru `README.md`.

Vyklonujte si repozitář k sobě na lokální disk do libovolné složky.

Vaším cílem je vytvořit ucelenou historii změn. Po každém kroku proveďte kontrolu stavu repozitáře a následně odešlete změny na server.

---

## Příprava projektu a dat

1. Vytvořte nový soubor s názvem `produkty.txt`.
2. Do tohoto souboru zapište tři libovolné názvy produktů (každý na nový řádek).
3. Vytvořte druhý soubor s názvem `sklad.py`. Do něj vložte následující kód:
```python
def vypis_sklad(seznam):
    for polozka in seznam:
        print(f"Skladem: {polozka} (Verze 1.0)")

if __name__ == "__main__":
    zbozi = ["Monitor", "Klávesnice", "Myš"]
    vypis_sklad(zbozi)
```

4. Vytvořte commit se zprávou: `"Inicializace: Seznam produktů a základní skladový skript"`.
5. Odešlete změny do vzdáleného repozitáře.

---

## Aktualizace verze a nová složka

1. Modifikujte soubor `sklad.py`: Změňte text ve funkci tak, aby vypisoval: `f"Položka: {polozka} - Aktualizováno v1.1"`
2. Vytvořte nový adresář s názvem `dokumentace`.
3. Uvnitř adresáře `dokumentace` vytvořte soubor `navod.txt` s textem: `Zde bude návod k použití aplikace.`
4. Vytvořte commit se zprávou: `"Aktualizace sklad.py na v1.1 a přidání složky dokumentace"`.
5. Odešlete změny na GitHub.

---

## Externí úprava a synchronizace

1. Přejděte do webového rozhraní svého GitHub repozitáře v prohlížeči.
2. Otevřete soubor `README.md` a upravte jej (Edit).
3. Na konec souboru přidejte větu: `Tento projekt slouží ke studiu základů verzování v Pythonu.`
4. Změnu uložte (commit) přímo ve webovém prostředí GitHubu.
5. Vraťte se do svého lokálního terminálu a synchronizujte svůj lokální repozitář tak, aby obsahoval změnu provedenou na webu.

---

## Reorganizace a finální úpravy

1. Odstraňte soubor `produkty.txt` z repozitáře i z disku (použijte na to příslušný git příkaz).
2. Modifikujte soubor `sklad.py`: Přidejte na úplně první řádek souboru Python komentář: `# Skript pro správu skladových zásob`.
3. Vytvořte commit se zprávou: `"Odstranění nepotřebného souboru a přidání komentáře do kódu"`.
4. Odešlete finální stav na server.

---

## Konec úlohy

Do odevzdávacího systému vložte odkaz (URL) na váš veřejný GitHub repozitář.
