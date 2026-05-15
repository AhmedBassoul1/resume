# Mon CV

Un curriculum vitae moderne créé avec LaTeX.

## 📄 À propos

Ce dépôt contient la source LaTeX de mon CV, structuré de manière modulaire pour faciliter les mises à jour et la maintenance.

## 📁 Structure du projet

```
├── cv-llt.tex              # Fichier principal du CV
├── settings.sty            # Configuration et style personnalisé
├── own-bib.bib             # Bibliographie
├── academique.tex          # Section académique
├── experience.tex          # Expérience professionnelle
├── education.tex           # Formation
├── skills.tex              # Compétences
├── profil.tex              # Profil personnel
├── misc.tex                # Sections diverses
└── README.md               # Ce fichier
```

## 🚀 Utilisation

### Prérequis

- **LaTeX** (TeX Live, MiKTeX ou MacTeX)
- **latexmk** (optionnel, mais recommandé)

### Compilation

Pour compiler le CV en PDF :

```bash
pdflatex cv-llt.tex
# ou avec latexmk
latexmk -pdf cv-llt.tex
```

Le fichier `cv-llt.pdf` sera généré dans le répertoire courant.

## ✏️ Modification

1. Ouvrez les fichiers `.tex` correspondants à la section à modifier
2. Faites vos changements
3. Recompilez le document

### Fichiers à éditer par section

- **Expérience** → `experience.tex`
- **Formation** → `education.tex` ou `academique.tex`
- **Compétences** → `skills.tex`
- **Profil** → `profil.tex`

## 🎨 Style

Le style du CV est défini dans `settings.sty`. Vous pouvez y personnaliser :
- Les couleurs
- Les polices
- La mise en page
- Les espacements

## 📝 Notes

- Les fichiers avec extensions `.aux`, `.log`, `.out`, etc. sont générés automatiquement et peuvent être supprimés
- Pour un meilleur contrôle de version, consultez le `.gitignore` pour exclure les fichiers de compilation

## 📧 Contact

Pour toute question ou amélioration, n'hésitez pas à me contacter !

---

**Dernière mise à jour** : 2026
