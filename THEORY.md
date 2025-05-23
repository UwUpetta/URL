## Co je to URL?

**URL** (*Uniform Resource Locator*) je adresa, která jednoznačně identifikuje a lokalizuje zdroj (např. webovou stránku, obrázek, video) na internetu.
![httpsbaset](https://github.com/user-attachments/assets/8751a009-7148-45b7-a6d9-e3470ca9afed)

Příklad URL:

https://salam.cz/baSET

---

## Kde se URL používá?

- Hypertextové odkazy na webu
- Stahování souborů
- Přesměrování a navigace
- API volání (např. REST API)

---

## Struktura URL

protokol://uživatel:heslo@host:port/cesta?dotaz#kotva


| Část        | Popis                                                                 |
|-------------|-----------------------------------------------------------------------|
| **Protokol**| Např. `http`, `https`, `ftp`, `mailto`, `file`             |
| **Host**    | Doména nebo IP adresa, např. `www.example.com`                       |
| **Port**    | (Volitelné) číslo portu, např. `443`                                 |
| **Cesta**   | Umístění souboru/adresáře na serveru, např. `/blog/clanek-1`         |
| **Parametry (Query)** | Parametry předávané např. formulářem: `?tag=java&autor=salam` |
| **Kotva (Fragment)** | Odkazuje na část stránky, např. `#uvod`                     |

---

## Příklad rozboru URL

https://www.moje-stranka.cz:443/produkty/hodinky?barva=cerna#recenze


- **Protokol:** `https`
- **Doména:** `www.moje-stranka.cz`
- **Port:** `443`
- **Cesta:** `/produkty/hodinky`
- **Dotaz (query):** `barva=cerna`
- **Kotva:** `recenze`

---

## Speciální znaky v URL

Některé znaky musí být zakódované (tzv. **URL encoding**):

| Znak | Kód  |
|------|------|
| Mezera | `%20` |
| `?`   | `%3F` |
| `&`   | `%26` |

? nebo & mají speciální význam, takže se s nimi musí opatrně

---


