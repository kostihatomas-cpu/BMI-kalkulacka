# 📱 Kompletní návod: Spuštění BMI Kalkulačky na GitHubu a instalace do mobilu

Tento návod vás provede krok za krokem od nahrání souborů na GitHub až po instalaci aplikace na plochu telefonu (Android i iPhone).

## 📂 Soubory v projektu

Pro správné fungování webu i mobilní PWA aplikace musíte mít v repozitáři tyto 4 soubory:

1. `index.html` *(hlavní kód aplikace)*
2. `manifest.json` *(konfigurace pro mobilní instalaci)*
3. `sw.js` *(Service Worker pro offline fungování)*
4. `README.md` *(tento návod)*

## 🚀 KROK 1: Vytvoření repozitáře na GitHubu

1. Přihlaste se na [GitHub.com](https://github.com).
2. Vpravo nahoře klikněte na tlačítko **`+`** a vyberte **New repository**.
3. **Repository name:** Zadejte název, například `bmi-kalkulacka`.
4. Ujistěte se, že je vybrána možnost **Public** (Veřejný).
5. Klikněte na zelené tlačítko **Create repository**.

## 📤 KROK 2: Nahrání souborů projektu

1. Na nově vytvořené stránce repozitáře klikněte na odkaz **uploading an existing file** *(nebo tlačítko Add file -> Upload files)*.
2. Přetáhněte sem všechny 4 soubory projektu:
   * `index.html`
   * `manifest.json`
   * `sw.js`
   * `README.md`
3. Dole klikněte na zelené tlačítko **Commit changes**.

## 🌐 KROK 3: Spuštění zdarma přes GitHub Pages

1. V horním menu vašeho repozitáře klikněte na **Settings** *(Nastavení)*.
2. V levém menu najděte a klikněte na **Pages**.
3. V sekci **Build and deployment**:
   * **Branch:** Zvolte `main` (nebo `master`).
   * Složku ponechte `/ (root)`.
4. Klikněte na tlačítko **Save**.
5. Počkejte 1 až 5 minut. Po obnovení stránky uvidíte zelený pruh s adresou vaší aplikace, například:
   `https://vase-jmeno.github.io/bmi-kalkulacka/`

## 📲 KROK 4: Instalace aplikace do mobilu (PWA)

Otevřete získanou adresu v prohlížeči ve svém mobilním telefonu:

### Android (Google Chrome / Edge)
1. Otevřete odkaz v prohlížeči Chrome.
2. Měla by se objevit výzva dole na obrazovce **"Přidat na domovskou obrazovku"** nebo **"Nainstalovat aplikaci"**.
3. Pokud se výzva neobjeví:
   * Klikněte na **3 tečky vpravo nahoře**.
   * Vyberte možnost **Nainstalovat aplikaci** nebo **Přidat na plochu**.

### iPhone / iOS (Safari)
1. Otevřete odkaz výhradně v prohlížeči **Safari**.
2. Dole uprostřed klikněte na tlačítko **Sdílet** *(ikona čtverečku se šipkou nahoru)*.
3. Posuňte nabídku dolů a zvolte **Přidat na plochu** *(Add to Home Screen)*.
4. Potvrďte kliknutím na **Přidat** vpravo nahoře.