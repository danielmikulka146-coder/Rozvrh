# Rozvrh

Neoficiální aplikace pro Android pro žáky škol, které používají EduPage. Rozvrh, známky, úkoly, zprávy
a další na jednom místě, rychleji a přehledněji než na webu. Data bere přímo z EduPage, bez vlastního serveru.

> Rozvrh není spojený s EduPage ani se společností asc Applied Software Consultants.

Tady jsou jen hotové verze aplikace ke stažení. Zdrojový kód je soukromý.

## Stažení a instalace

**[Stáhnout nejnovější verzi](https://github.com/danielmikulka146-coder/Rozvrh/releases/latest)** (soubor `.apk` v části Assets)

1. Otevři odkaz v telefonu a stáhni soubor `Rozvrh-….apk`.
2. Otevři stažený soubor. Telefon se zeptá, jestli smí prohlížeč (nebo Soubory) instalovat aplikace:
   povol to v nastavení, které se otevře, a vrať se zpátky.
3. Když Google Play Protect upozorní na neznámou aplikaci, zvol **Přesto nainstalovat**. Upozornění
   se ukazuje u každé aplikace, která není z Google Play.
4. Otevři aplikaci **Rozvrh** a přihlas se svým účtem EduPage (adresa školy, e-mail nebo jméno a heslo).

**Potřebuješ:** Android 9 nebo novější a účet EduPage.

**Nová verze:** stáhni novější `.apk` a nainstaluj ho přes stávající aplikaci. Účty, nastavení i data zůstanou.
Co je nového, je v [CHANGELOG.md](CHANGELOG.md) a po aktualizaci i přímo v aplikaci.

**iPhone:** zatím ne, verze pro iOS se připravuje.

## Co aplikace umí

- **Rozvrh** na týden se suplováním a zrušenými hodinami, rozvrhy jiných tříd, učitelů a učeben,
  detail hodiny s probraným učivem.
- **Známky** s průměry, kalkulačkou „co když“ a výpočtem, co potřebuješ na lepší známku.
- **Docházka** v procentech po předmětech a podání omluvenky.
- **Úkoly, písemky a projekty**: zadání a materiály v aplikaci, komentáře a odevzdání odpovědi.
- **Zprávy**: čtení, odpovídání a psaní nových.
- **Jídelna** ve Strava.cz: jídelníček, objednávky a konto.
- **ePeněženka**: poplatky a historie, placení QR Platbou v bankovní aplikaci.
- **Widgety** na plochu a **oznámení** (pozdější začátek výuky, nové zprávy, připomínky úkolů).
- **Vzhled**: vlastní barva nebo barvy z tapety a několik stylů (Plakát, Vaporwave jádro, Japonský, Belle Époque).
- **Víc účtů**, ochrana účtu PINem nebo otiskem, přihlášení počítače QR kódem.
- Pro SPŠ Zlín navíc kontakty na vyučující, tisk na školní tiskárnu a hledání volné učebny.

## Soukromí

- Heslo i stažená data jsou jen v telefonu, zašifrovaná klíčem z Android Keystore.
- Aplikace nemá vlastní server a nic neposílá autorům. Komunikuje jen s EduPage tvé školy, se Strava.cz
  (když se do jídelny přihlásíš) a u SPŠ Zlín se stránkami školy (kontakty na vyučující).
- Zpětná vazba z aplikace vede na formulář, který vyplňuješ sám.

## Chyby a nápady

Tlačítkem zpětné vazby na domovské stránce aplikace, nebo v [Issues](https://github.com/danielmikulka146-coder/Rozvrh/issues/new/choose).
Do hlášení nepiš heslo ani osobní údaje (známky, jména, zprávy) a na snímcích obrazovky je zakryj.

## Autoři a licence

© 2026 Filip Dleštík a Daniel Mikulka. Aplikace je zdarma pro osobní použití, podmínky jsou v [LICENSE](LICENSE).
Knihovny a písma třetích stran mají vlastní licence; jejich seznam a texty jsou v aplikaci
(Nastavení → O aplikaci).
