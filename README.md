# Tekstilna enciklopedija — šta nastaje iz tekstilnog otpada (100 projekata)

Javna strana: https://3esign.github.io/tekstilna-enciklopedija/

Samostalan, statičan sajt: `index.html` (sav stil u strani, bez skripti i bez spoljnih poziva) i `foto/` (100 fotografija, svaka ≤ 300 KB, duža strana ≤ 1600 px, bez EXIF-a). Kartica svakog projekta vodi na izvorni sajt projekta i na izvor fotografije.

## Poreklo
Sadržaj je nastao u predmetu Inkluzivni studio (repo `3esign/inclusive-studio`, komit `fdcbc90`, 03.11.2026) kao dodatak Tekstilnom atlasu. Izmešten je 08.11.2026 u zaseban projekat jer nije gradivo predmeta i nije prolazio ugovor školjke tog sajta (11 testova), a nosio je 47 MB na Pages predmeta. Tekstilni atlas ostaje u inclusive-studio i vodi ovamo.

## Mediji
`foto/MANIFEST.json` nosi za svaku fotografiju sha256 i veličinu originala i optimizovane kopije, dimenzije i kvalitet. Originali su sačuvani van javnog repoa, u privatnom arhivu Svemira (`data/karantin-slika/tekstilna-enciklopedija-originali-2026-11-08/`, sa sopstvenim MANIFEST-om). Nijedan original nije obrisan.

## Rad
- Nova fotografija: optimizovati pre ulaska (isti budžet), upisati u `foto/MANIFEST.json`, original u arhiv.
- Objava: `git push origin main` (Pages služi granu `main`, koren).
