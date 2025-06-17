# Healthcare UI Kit

Healthcare UI Kit è una raccolta di componenti e icone per interfacce web in ambito sanitario, progettata per essere facilmente integrata in progetti HTML/CSS.

## Tecnologie utilizzate

- **HTML5**
- **CSS3** (custom e Bootstrap override)
- **Bootstrap 5** (solo CSS/JS, senza dipendenze da jQuery)
- **Font Awesome** (per alcune icone)
- **Icone SVG custom** (in `css/healthcare-icons.css`)

Il kit include stili per bottoni, badge, alert, card e icone specifiche per il settore sanitario.

Ne è stata verificata la compatibilità con i principali browser moderni (Chrome, Firefox).

L'**accessibilità** è stata considerata, con l'uso di colori ad alto contrasto e supporto per screen reader. 
Ad esempio, il contrasto tra testo e sfondo per `.bg-dark` e `.text-light` è di circa 13.7:1, ben superiore al minimo WCAG (4.5:1 per testo normale, 3:1 per testo grande).  
Tutti i colori principali (primario, secondario, danger, ecc.) usano sempre testo bianco su sfondo scuro o viceversa, con rapporti di contrasto generalmente superiori a 4.5:1. 

La responsività è garantita tramite le classi di Bootstrap, che permettono un layout fluido su dispositivi desktop e mobile. Nella pagina in `docs/index.html` è possibile testare diversi esempi di utilizzo su schermi di diverse dimensioni.

## Come utilizzare

1. **Clona o scarica il repository.**
2. **Includi i file CSS nel tuo HTML:**
   ```html
   <link rel="stylesheet" href="css/healthcare-ui.css">
   <link rel="stylesheet" href="css/healthcare-icons.css">
   ```
3. **Includi Bootstrap JS (opzionale per componenti interattivi):**
   ```html
   <script src="js/bootstrap.js"></script>
   ```
4. **Utilizza le classi dei componenti:**
    - Bottoni: `.btn`, `.btn-primary`, `.btn-success`, ecc.
    - Badge: `.badge`, `.badge-success`, ecc.
    - Alert: `.alert`, `.alert-primary`, ecc.
    - Card: `.card`, `.card-header`, ecc.
    - Icone: `<i class="hc-patient"></i>`, `<i class="hc-doctor"></i>`, ecc.

## Esempio di utilizzo

```html
<button class="btn btn-primary">Button primario</button>
<span class="badge badge-success">Nuovo</span>
<i class="hc-stethoscope"></i>
```

## Personalizzazione

Puoi modificare i colori principali tramite le variabili CSS definite in `healthcare-ui.css` (`--hc-primary`, `--hc-success`, ecc.).

## Licenza

Questo progetto è rilasciato sotto la licenza MIT. Consulta il file `LICENSE.md` per maggiori dettagli.

## Documentazione

Per una documentazione completa, consulta il file `docs/index.html` che contiene esempi di utilizzo e spiegazioni dettagliate su ogni componente.

## Contribuire

Se desideri contribuire al progetto, puoi:
- Segnalare problemi o bug tramite le issue su GitHub.
- Inviare pull request con nuove funzionalità o correzioni.