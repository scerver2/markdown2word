# MD ⇄ DOCX Converter

Convertidor bidireccional entre Markdown i Word amb previsualització en temps real.

## ✨ Característiques

- **Conversió bidireccional**: Markdown → Word i Word → Markdown
- **Previsualització en temps real**: Visualitza com quedarà el document mentre escrius
- **Suport complet de símbols**:
  - Lletres gregues: α, β, γ, δ, ε, ζ, η, θ, λ, μ, π, σ, ω, Δ, Σ, Ω
  - Subíndexs: H₂O, CO₂
  - Superíndexs: E=mc², x²
  - Símbols matemàtics: ∞, ≤, ≥, ≠, ±, ×, ÷
- **Personalització de colors**: Canvia el color dels títols del document Word
- **Càrrega d'arxius**: Puja arxius .md o .docx directament
- **Suport de format Markdown**:
  - Capçaleres (H1-H6)
  - Negreta, cursiva, subratllat
  - Llistes (ordenades i desordenades)
  - Codi (inline i blocs)
  - Taules
  - Enllaços
  - Cites (blockquotes)

## 🚀 Desplegament a GitHub Pages

### Opció 1: Des de la interfície web de GitHub

1. Crea un nou repositori a GitHub
2. Puja l'arxiu `index.html`
3. Vés a `Settings` → `Pages`
4. A "Source", selecciona la branca `main` i la carpeta `/root`
5. Fes clic a `Save`
6. La pàgina estarà disponible a: `https://[el-teu-usuari].github.io/[nom-del-repo]`

### Opció 2: Des de la línia de comandes

```bash
# Crea un nou repositori local
git init

# Afegeix l'arxiu
git add index.html README.md

# Fes el primer commit
git commit -m "Initial commit: MD ⇄ DOCX Converter"

# Connecta amb el repositori remot (crea'l abans a GitHub)
git remote add origin https://github.com/[el-teu-usuari]/[nom-del-repo].git

# Puja els canvis
git branch -M main
git push -u origin main

# Activa GitHub Pages des de Settings → Pages
```

### Opció 3: Amb GitHub Desktop

1. Obre GitHub Desktop
2. File → New Repository
3. Afegeix l'arxiu `index.html` al repositori
4. Fes commit dels canvis
5. Publica el repositori a GitHub
6. Activa GitHub Pages des de la configuració del repositori

## 📖 Com utilitzar-lo

### Markdown → Word

1. Selecciona el mode "Markdown → Word"
2. Escriu o enganxa el teu contingut Markdown a l'àrea d'entrada
   - O puja un arxiu .md amb el botó "📁 Pujar arxiu"
3. Veuràs la previsualització al panell de la dreta
4. (Opcional) Canvia el color dels títols amb el selector de color
5. Fes clic a "⚡ Convertir a Word"
6. Es descarregarà automàticament el fitxer `document.docx`

### Word → Markdown

1. Selecciona el mode "Word → Markdown"
2. Puja un arxiu .docx amb el botó "📁 Pujar arxiu"
   - O enganxa el contingut directament
3. Veuràs la previsualització HTML al panell de la dreta
4. Fes clic a "⚡ Convertir a Markdown"
5. Es descarregarà automàticament el fitxer `document.md`

## 🎨 Exemples de Markdown

### Capçaleres
```markdown
# Títol 1
## Títol 2
### Títol 3
```

### Format de text
```markdown
**Negreta**
*Cursiva*
***Negreta i cursiva***
~~Ratllat~~
`codi inline`
```

### Llistes
```markdown
- Element 1
- Element 2
  - Subelement

1. Primer
2. Segon
3. Tercer
```

### Símbols especials
```markdown
- Grec: α β γ δ ε
- Matemàtiques: x² = 4, H₂O
- Símbols: ∞ ≠ ≤ ≥ ±
```

### Codi
````markdown
```python
def hola():
    print("Hola món!")
```
````

### Taules
```markdown
| Columna 1 | Columna 2 |
|-----------|-----------|
| Valor 1   | Valor 2   |
```

### Enllaços
```markdown
[Text de l'enllaç](https://example.com)
```

### Cites
```markdown
> Aquesta és una cita
```

## 🔧 Tecnologies utilitzades

- **HTML5/CSS3**: Estructura i estil
- **JavaScript (ES6+)**: Lògica de l'aplicació
- **Showdown.js**: Conversió de Markdown a HTML
- **Docx.js**: Generació de documents Word
- **Mammoth.js**: Lectura de documents Word
- **FileSaver.js**: Descàrrega d'arxius

## 📝 Notes tècniques

- Tots els símbols Unicode són suportats (grec, matemàtics, subíndexs, etc.)
- El color dels títols només s'aplica en la conversió a Word
- La previsualització mostra com quedarà el document final
- Els arxius es processen completament al navegador (sense servidor)

## 🌐 Compatibilitat

- Chrome/Edge: ✅ Totalment compatible
- Firefox: ✅ Totalment compatible
- Safari: ✅ Totalment compatible
- Opera: ✅ Totalment compatible

## 📄 Llicència

Aquest projecte és de codi obert i lliure d'utilitzar.

## 🤝 Contribucions

Les contribucions són benvingudes! Si tens suggeriments o millores:

1. Fes un fork del repositori
2. Crea una branca amb la teva funcionalitat (`git checkout -b feature/nova-funcio`)
3. Fes commit dels teus canvis (`git commit -m 'Afegeix nova funció'`)
4. Puja la branca (`git push origin feature/nova-funcio`)
5. Obre un Pull Request

## 🐛 Informar d'errors

Si trobes algun error, si us plau obre un issue al repositori de GitHub amb:
- Descripció de l'error
- Passos per reproduir-lo
- Navegador i versió utilitzats

---

Fet amb ❤️ per a la comunitat
