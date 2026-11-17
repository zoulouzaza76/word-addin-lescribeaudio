# Le Scribe Audio — Complément Officiel Microsoft Word (`Office.js` Web Add-in)

Complément panneau latéral (`Taskpane`) open-source sous licence **MIT** pour **Microsoft Word** (Windows, macOS et Word sur le Web — Microsoft 365), édité par [**LE SCRIBE AUDIO**](https://lescribeaudio.com).

## Fonctionnalités (100 % locales dans le volet Word `Office.js`)

1. **Nettoyage instantané de sous-titres `.SRT` et `.VTT` (Teams, Zoom, Whisper)** : suppression des numéros de séquences, horodatages techniques `-->`, balises `<v Locuteur>` et fusion intelligente des prises de parole consécutives d'un même intervenant avant insertion directe au curseur dans le document Word actif (`Word.run`).
2. **Typographie française automatique** : application des espaces fines insécables (`U+202F` avant `: ; ? ! %`) et des espaces insécables (`U+00A0` autour des guillemets français `« ... »` et du symbole `€`).
3. **Export corpus étoilé `IRaMuTeQ` (`**** *entretien_word`)** : formatage direct pour l'analyse lexicométrique et les logiciels CAQDAS en sciences humaines et sociales.

## Confidentialité & Architecture (RGPD / nLPD / Loi 25)

- Le nettoyage `.SRT`/`.VTT`, la typographie française et le formatage `IRaMuTeQ` s'exécutent **entièrement en mémoire locale** dans le volet `Office.js` (`https://lescribeaudio.com/word-addin/taskpane.html`), sans téléversement serveur ni télémétrie publicitaire.
- Pour la pré-transcription audio/vidéo longue durée en 2 passes sur [lescribeaudio.com](https://lescribeaudio.com) (divisant par 2 le temps de rédaction des procès-verbaux et entretiens — 2 à 3 h de relecture par heure d'audio contre 4 à 7 h en frappe manuelle, ou option de correction humaine à 60 € HT/h par deux transcripteurs successifs), les fichiers sont hébergés en France chez **OVHcloud (`AES-256`)** avec suppression définitive en 1 clic, et l'inférence est opérée via **Google Cloud Vertex AI (en région Europe)** sans conservation ni entraînement sur les données (*Zero Data Retention*, éditeur américain soumis en droit au *US Cloud Act*).

## Liens Utiles

- [Guide Dictée Vocale & Transcription Microsoft Word](https://lescribeaudio.com/dictee-vocale-transcription-word)
- [Comparatif des Logiciels de Transcription Automatique](https://lescribeaudio.com/logiciels-transcription-automatique-tutoriel-comparatif)
- [Outils Gratuits Open-Source (RGAA 4.1, SRT/VTT, IRaMuTeQ)](https://lescribeaudio.com/outils)
- **Éditeur** : LE SCRIBE AUDIO (`RCS Rennes 890 049 927`) · Tél. : `09 61 44 46 64` (`+33 9 61 44 46 64`) · `info@lescribeaudio.com`
