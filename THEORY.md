
## URL

**URL** (*Uniform Resource Locator*) je jednoznačná adresa zdroje na internetu – může to být webová stránka, obrázek, video, dokument apod. Je to adresa, kterou vidíte nahoře v adresním řádku vašeho webového prohlížeče.
![image](https://github.com/user-attachments/assets/4a4d8c7c-ff84-418a-8a0b-282ba7c5a7ad)

Příklad URL:

```
https://haxagon.xyz/challenge/url
```

URL není jen „adresní řádek“ – je to základní stavební prvek celého webu.

---

## Kde se URL používá?

Možná si to neuvědomujete, ale URL se používá na mnoha místech:

| Situace                    | Popis                                                                 |
|----------------------------|-----------------------------------------------------------------------|
| **Kliknutí na odkaz**      | Otevřete stránku s danou URL. Např. ve vyhledávači nebo článku.       |
| **Formuláře**              | Po odeslání dat se URL může změnit a obsahovat parametry.            |
| **API volání**             | Programy a aplikace si posílají data pomocí URL (např. REST API).    |
| **Stahování souborů**      | Když kliknete na tlačítko „Stáhnout PDF“, spustí se URL k souboru.    |
| **QR kódy**                | QR kód obvykle obsahuje URL – po načtení Vás přesměruje na web.       |

---

## Části URL

Každá URL má jasně danou strukturu. Pojďme si ji vysvětlit postupně:

### Protocol

Určuje, jaký komunikační způsob se použije. Nejčastěji:
- `http` (nezabezpečené spojení)
- `https` (zabezpečené spojení)
- Méně často: `ftp`, `mailto`, `file`

**Příklad:**  
`https://` znamená, že komunikace probíhá bezpečně přes SSL.

---

### Domain(Doména)

Zpravidla název serveru nebo domény, kde je obsah uložen.

**Příklad:**  
`www.haxagon.xyz` – doména serveru.

---

### Port

Pokud se používá jiný port než výchozí, je součástí URL (většinou není třeba uvádět).

**Příklad:**  
`:443` – výchozí port pro HTTPS.

---

### Path(Cesta)

Určuje, kde přesně se obsah na serveru nachází.

**Příklad:**  
`/challenge/URL` – konkrétní stránka nebo složka.

---

### Fragment

Odkazuje na konkrétní část stránky – třeba záložku nebo nadpis.

**Příklad:**  
`#kontakt` – proskroluje stránku na sekci s ID `kontakt`.

---

## Příklad rozboru URL

Rozložíme si konkrétní URL:

```
https://www.moje-stranka.cz:443/produkty/hodinky#recenze
```

| Část       | Význam                        |
|------------|-------------------------------|
| `https`    | Protocol                      |
| `www.moje-stranka.cz` | Host               |
| `:443`     | Port                          |
| `/produkty/hodinky` | Path                |
| `#recenze` | Fragment                     |

---

## Shrnutí – struktura URL

| Část        | Popis                                                                 |
|-------------|-----------------------------------------------------------------------|
| **Protocol**| Např. `http`, `https`, `ftp`, `mailto`, `file`                       |
| **Host**    | Doména nebo IP adresa, např. `www.example.com`                       |
| **Port**    | (Volitelné) číslo portu, např. `443`                                 |
| **Path**    | Umístění souboru/adresáře na serveru, např. `/blog/clanek-1`         |
| **Fragment**| Odkazuje na část stránky, např. `#uvod`                              |

---

## Závěr

URL je základní stavební kámen internetu. Znalost její struktury a použití Vám pomůže lépe pochopit, jak funguje web, API nebo třeba filtrování produktů v e-shopech. Pozornější z vás si možná všimli, že se v url často nachází znaky jako `&` nebo `?` o tom co znamenají si povíme příště...
