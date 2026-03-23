# 🚀 Magic Marketing Suite - AI Agent Skills

Benvenuto nel repository ufficiale della **Magic Marketing Suite**! 
Questa repository contiene un ecosistema di Skill collegate tra loro per trasformare il tuo Agente AI (Claude Code, Cursor, OpenCode, Gemini, ecc.) in un vero e proprio team di Performance Marketing.

---

## 📦 Installazione Rapida

Per installare l'intera suite nel tuo progetto locale, apri il terminale alla radice del tuo progetto e digita:

```bash
npx skills add richardteatime/Magic-Marketing-Suite --skill '*'
```
*(L'utility scaricherà e mapperà automaticamente tutte e 4 le skill nel tuo workspace).*

---

## 🛠 Le Skill Incluse

### 1. 🧠 Performance Marketing Analysis (`performance-marketing-analysis`)
La mente strategica dell'intera suite. Un Senior Media Buyer capace di analizzare il prodotto, i competitor e restituirti una strategia chiavi in mano.
- **Che cosa fa:** Analizza la tua Landing Page, usa le API di **Apify** per estrarre fino a 100 ads native e vincenti dei tuoi competitor, impagina la Pricing Strategy e partorisce 4 Buyer Personas (Angoli di marketing). Infine scrive 5 varianti Copy e 4 Script Video.
- **Integrazioni:** Se gli fornisci la chiave `ELEVENLABS_API_KEY`, si connette in automatico alla Skill Text-to-Speech per generare seduta stante i file audio `.mp3` dei 4 video ads avvalendosi delle tue voci custom preferite.

### 2. 🗣 Text-to-Speech (`text-to-speech`)
Skill ufficiale basata su **ElevenLabs**. Permette all'AI di dialogare direttamente con le API vocali per clonare voci, applicare settaggi personalizzati di narrazione Advertising e fornire l'audio ad altissima conversione pronto al montaggio.

### 3. 🎨 Ad Creative (`ad-creative`)
Il ramo focalizzato sulla produzione visiva e testuale granulare. Utilizza questa skill se vuoi scalare i tuoi ad copy esistenti, generare batch infiniti di nuovi Headings, opzioni descrittive da testare in A/B testing e brainstormare concetti visivi.

### 4. 🪙 Paid Ads (`paid-ads`)
Il cruscotto nevralgico della Media Buying. Usata per pianificare budget, metriche avanzate (ROAS, CPA) e targeting specifico su Meta Ads, Google Ads, LinkedIn e TikTok. Lavora a stretto contatto con la *Performance Marketing Analysis* per le ottimizzazioni in corso d'opera.

---

## ⚙️ Setup & Requisiti

Per sbloccare il vero potenziale (Modalità God) della `performance-marketing-analysis`, dovrai fonirle due API Keys al primissimo avvio:
1. `APIFY_TOKEN`: Per intercettare e hackerare le campagne della concorrenza nella libreria Meta Ads. *(Il costo dello script è impostato su "sicurezza estrema" e sfiora appena $0.05 a ricerca).*
2. `ELEVENLABS_API_KEY`: Per la generazione rapida dei podcast/voiceover VSL da mandare direttamente a videomaker o editor.

Se non disponi di queste chiavi, la skill continuerà a funzionare regolarmente basando la propria strategia sulla profonda Knowledge Base interna dell'AI e sui dati della landing page del prodotto.

---
*Progettato e ottimizzato per workflow ad alta conversione nel mercato Direct Response.*
