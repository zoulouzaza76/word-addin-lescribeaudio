# Soumission Clé en Main — Microsoft AppSource (`appsource.microsoft.com` — `DR 96`, `0 €`) · LibreOffice (`DR 89`) · Obsidian (`DR 86`)

> **Atout immédiat :** Votre compte **Microsoft Partner Center** (`info@lescribeaudio.com` · `Seller ID: 97358140`) est déjà actif et vérifié. Il suffit d'activer le programme gratuit **Microsoft 365 & Copilot / Office Store** (`0 €`) pour téléverser `manifest.xml` !

---

## 1. Microsoft AppSource — Complément Officiel Microsoft Word (`DR 96`)

### Prérequis techniques déjà déployés dans ce dépôt :
- **Manifeste officiel Office Add-in XML :** `open-source/word-addin-lescribeaudio/manifest.xml`
- **Volet Web (`Office.js` 100 % local, zéro collecte de données) :** `frontend/public/word-addin/taskpane.html` (`https://lescribeaudio.com/word-addin/taskpane.html`)
- **Icônes officielles 5 résolutions :** `icon-16.png`, `icon-32.png`, `icon-64.png`, `icon-80.png`, `icon-128.png` dans `frontend/public/word-addin/`
- **En-têtes Nginx configurés (`nginx/nginx.conf`) :** `frame-ancestors` autorisant explicitement `*.officeapps.live.com`, `*.office.com`, `*.office365.com`, `*.microsoft365.com` et `*.sharepoint.com`.

### Étapes de dépôt en 5 minutes (après `deploy.sh` en production) :
1. Ouvrir `https://partner.microsoft.com/dashboard/marketplace-offers/overview` (compte `Seller ID: 97358140`).
2. Cliquer sur **+ New offer** → **Office Add-in**.
3. **Offer ID :** `le-scribe-audio-word-srt-fr` · **Offer alias :** `Le Scribe Audio — Outils SRT & Typographie FR`.
4. **Package :** téléverser `open-source/word-addin-lescribeaudio/manifest.xml`.
5. **Properties :**
   - **Categories :** `Productivity`, `Document Management`
   - **Legal / Privacy Policy URL :** `https://lescribeaudio.com/confidentialite`
   - **Terms of Use URL :** `https://lescribeaudio.com/cgu`
   - **Support URL :** `https://lescribeaudio.com/outils`
   - **Pricing :** `Free` (`No additional purchase required` — le complément fonctionne 100 % hors compte et gratuitement).
6. **Notes for certification (copier-coller aux testeurs Microsoft) :**
   > *This free Word taskpane add-in runs 100% locally in the client browser/webview with zero login, zero API key, and zero server transmission. To test: 1) Click "Outils SRT & Typo FR" on the Home ribbon tab. 2) Paste any WebVTT or SRT subtitle sample into Section 1 and click "Insérer proprement dans Word" to insert merged speaker turns with French non-breaking spaces into the active document. 3) Click "Appliquer la typographie française au document" in Section 2 to normalize French punctuation spacing and view word/duration estimates.*

---

## 2. LibreOffice Extensions (`extensions.libreoffice.org` — `DR 89`, `0 €`)

- **Archive prête à déposer :** `open-source/libreoffice-srt-cleaner-fr/srt-vtt-cleaner-fr-1.0.0.oxt`
- **Portail officiel The Document Foundation :** `https://extensions.libreoffice.org/` → *Login / Register* → *Add New Extension*
- **Champs à copier-coller :**
  - **Title :** `SRT / VTT Cleaner & Typographie Française (IRaMuTeQ / PV)`
  - **Category :** `Writer` (Traitement de texte standard du SILL / mairies françaises)
  - **License :** `MIT`
  - **Homepage / Documentation URL :** `https://lescribeaudio.com/nettoyeur-transcription-vtt-srt-teams-zoom-word` & `https://github.com/zoulouzaza76/srt-vtt-cleaner-fr`

---

## 3. Obsidian Community Plugins (`obsidian.md` — `DR 86`) & Zotero SHS (`zotero.org` — `DR 87`)

- **Dossier prêt :** `open-source/obsidian-srt-iramuteq-fr/` (`manifest.json`, `main.js`, `versions.json`, `styles.css`, `README.md`)
- **Publication :** Créer le dépôt public `zoulouzaza76/obsidian-srt-iramuteq-fr`, attacher `main.js`, `manifest.json` et `styles.css` à la Release GitHub `1.0.0`, puis ouvrir une Pull Request d'1 ligne dans `https://github.com/obsidianmd/obsidian-releases/blob/master/community-plugins.json`.
