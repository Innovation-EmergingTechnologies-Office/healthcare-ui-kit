# Healthcare UI Kit

Healthcare UI Kit è una raccolta di componenti e icone per interfacce web in ambito sanitario, progettata per essere facilmente integrata in progetti HTML/CSS.

## Tecnologie utilizzate

- **HTML5**
- **CSS3** (custom e Bootstrap override)
- **Bootstrap 5** (solo CSS/JS, senza dipendenze da jQuery)
- **Font Awesome** (per alcune icone)
- **Icone SVG custom** (in `css/healthcare-icons.css`)

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

MIT