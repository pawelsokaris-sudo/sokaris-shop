# e-xtra.pl / oprogramowanie.e-xtra.pl — Full Audit

## Hosting & Stack

| Parametr | Wartość |
|----------|---------|
| IP | 185.208.164.129 |
| Hosting | Cyber_Folks (shared, LiteSpeed) |
| SSL | Let's Encrypt (wygenerowany 2026-04-19) |
| SSH | Port 222, user v118023 |
| Silnik | Custom PHP (framework yovalS) |
| Baza | MySQL v118023_extrapl |
| Multi-tenant | TAK — platforma hostuje ~92 witryn (sklepów) |

## Witryna Sokaris

| Parametr | Wartość |
|----------|---------|
| Witryna ID | 597 |
| Subdomena | oprogramowanie.e-xtra.pl |
| Folder | wit/_oprogramowanie |
| Status | **odblokowana** (aktywna) |
| Produktów | 14 aktywnych |
| URL base | https://www.oprogramowanie.e-xtra.pl/index.php |

## Katalog Produktów (14 aktywnych)

| KOD | Nazwa | Netto | Brutto | Kategoria |
|-----|-------|-------|--------|-----------|
| 3 | Fakturant - licencja bezterminowa | 145.53 | 179.00 | Fakturant |
| 54 | SOKARIS Faktura-NT - licencja roczna | 158.53 | 194.99 | Faktura-NT |
| 107 | Moduł fiskalny - licencja bezterminowa | 96.75 | 119.00 | Fakturant |
| 235 | Fakturant - Roczna opieka serwisowa | 88.62 | 109.00 | Fakturant |
| 260 | Sokaris Sapio - licencja roczna | 568.29 | 699.00 | Sapio |
| 268 | Faktura-NT - Roczny dostęp do aktualizacji | 104.88 | 129.00 | Faktura-NT |
| 269 | Sapio - Roczna licencja na aktualizacje | 97.55 | 119.99 | Sapio |
| 323 | Moduł eksportu danych do systemów księgowych | 300.00 | 369.00 | Faktura-NT |
| 332 | Pakiet migracyjny FNT + opieka + KSeF Smart | 397.56 | 489.00 | Fakturant |
| 338 | Moduł JPK - licencja roczna | 86.99 | 107.00 | Faktura-NT |
| 349 | Moduł księgowy - licencja roczna | 243.09 | 299.00 | Faktura-NT |
| 353 | Moduł księgowy - licencja miesięczna | 24.38 | 29.99 | Faktura-NT |
| 380 | KSeF smart - licencja roczna | 240.00 | 295.20 | Faktura-NT |
| 2179 | SOKARIS Faktura-NT - siedmioletnia | 698.37 | 859.00 | Faktura-NT |

## Kategorie (grupy URL)

| grupy= | Kategoria |
|--------|-----------|
| 56 | Fakturant |
| 57 | Faktura-NT |
| 58 | Sapio |

## Statystyki globalne platformy

| Metryka | Wartość |
|---------|---------|
| Wszystkie produkty | 26,498 |
| Wszystkie zamówienia | 21,010 |
| Wszyscy użytkownicy | 10,814 |
| Witryny (sklepy) | ~92 |

## Integracja

- FTP import/export: impexp@e-xtra.pl → ftp.sokaris.pl
- SOAP: soapserver.php (Sapio integration)
- dbwtunnel.php (remote DB debugging)
- Brak bramki płatności online (przelew bankowy)
