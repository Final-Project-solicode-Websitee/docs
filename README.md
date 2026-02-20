---
marp: true
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
style: |
  section {
    font-size: 22px;
    color: #333;
    line-height: 1.6;
    padding: 60px 80px;
  }
  h1 { color: #088dc7; font-size: 2.8em; margin-top: 40px; }
  h2 { color: #088dc7; font-size: 2em; border-bottom: 2px solid #088dc7; margin-bottom: 40px; }
  h3 { color: #555; font-size: 1.1em; font-weight: 400; }
  li { margin-bottom: 8px; }
  strong { color: #088dc7; font-weight: bold; }
  code { background: #f4faff; color: #088dc7; padding: 2px 8px; border-radius: 4px; }
  table { width: 100%; border-collapse: collapse; }
  th { background: #088dc7; color: white; padding: 10px 14px; }
  td { padding: 10px 14px; border-top: 1px solid #e2e8f0; }
  tr:nth-child(even) { background: #f4faff; }
  blockquote { border-left: 5px solid #088dc7; background: #f4faff; padding: 10px 20px; border-radius: 4px; color: #3d3d3d; font-style: italic; }
  .sommaire-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-top: 20px;
  }
  .sommaire-item {
    display: flex;
    align-items: center;
    background: #f4faff;
    border-radius: 12px;
    padding: 15px 20px;
    border-left: 5px solid #088dc7;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  }
  .sommaire-num {
    background: #088dc7;
    color: white;
    width: 35px;
    height: 35px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
    font-weight: bold;
    margin-right: 15px;
    flex-shrink: 0;
  }
  .sommaire-text {
    font-size: 1.1em;
    font-weight: 600;
    color: #3d3d3d;
  }
  .highlight { color: #088dc7; font-weight: bold; }
header: 'Méthode de Travail — Organisation du Projet'
footer: '© 2026 Team Project'
---

# **Organisation du Projet**
### Méthode de travail & dépôts spécialisés
**Réalisé par :** <span class="highlight">Solidevs 26</span>  
**Encadré par :** <span class="highlight">M. ESSARRAJ Fouad</span>  
**Date :** 20 / 02 / 2026

---

## Sommaire

<div class="sommaire-grid">
  <div class="sommaire-item">
    <div class="sommaire-num">1</div>
    <div class="sommaire-text">Pourquoi cette organisation ?</div>
  </div>
  <div class="sommaire-item">
    <div class="sommaire-num">2</div>
    <div class="sommaire-text">Les 7 dépôts</div>
  </div>
  <div class="sommaire-item">
    <div class="sommaire-num">3</div>
    <div class="sommaire-text">Analyse & Conception</div>
  </div>
  <div class="sommaire-item">
    <div class="sommaire-num">4</div>
    <div class="sommaire-text">Maquettage & Développement</div>
  </div>
  <div class="sommaire-item">
    <div class="sommaire-num">5</div>
    <div class="sommaire-text">Documentation & Communication</div>
  </div>
  <div class="sommaire-item">
    <div class="sommaire-num">6</div>
    <div class="sommaire-text">Contribution</div>
  </div>
</div>

---

## 1. Pourquoi cette organisation ?

Travailler en équipe sur un projet complexe nécessite une **structure claire**.

Chaque dépôt a un **rôle précis** — chaque contribution a sa place :

- ✅ Collaborer sans bloquer les autres
- ✅ Garder un historique propre et lisible
- ✅ Savoir **où trouver** chaque ressource

---

## 2. Les 7 dépôts

| Dépôt | Rôle |
|---|---|
| 📁 `analyse` | Recherche & besoins |
| 📁 `conception` | Architecture de base de données |
| 📁 `maquettage` | Design & UI/UX |
| 📁 `app` | Code de l'application |
| 📁 `docs` | Méthode de travail |
| 📁 `labs` | Présentations de labs |
| 📁 `presentation` | Bilan global du projet |

---

## 3. Analyse & Conception

**📁 `analyse`** — Comprendre le problème
- Compte rendu d'empathie
- Cahier des charges & cas d'utilisation
- Définition du problème & idéation

**📁 `conception`** — Structurer la solution
- Diagramme de classe
- Modélisation des entités et relations

---

## 4. Maquettage & Développement

**📁 `maquettage`** — Design avant de coder
- Prototypes graphiques statiques

**📁 `app`** — Le code source
- Implémentation des fonctionnalités
- Intégration des maquettes validées

---

## 5. Documentation & Communication

- **📁 `docs`** : méthode de travail & guides de l'équipe
- **📁 `labs`** : présentation de chaque session de lab
- **📁 `presentation`** : bilan global du projet

---

## 6. Contribution

1. **Fork** le dépôt concerné sur GitHub
2. Effectuez vos **modifications** dans votre fork
3. Soumettez une **Pull Request**
4. Labs hors organisation → dépôt **public**

> PR examinées par <span class="highlight">Yasmine</span> ou <span class="highlight">Abdelhay</span>

---

# Merci !

### → Consultez `docs` pour tous les détails