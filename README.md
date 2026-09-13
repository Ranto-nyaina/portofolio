# 💼 Portfolio — FANOMEZANTSOA Rantoniaina Harlivah

Site portfolio personnel présentant le profil, les compétences et les projets de **Rantoniaina Harlivah Fanomezantsoa**, développeur full-stack en spécialisation **intelligence artificielle et sécurité informatique**.

🔗 **Site en ligne :** https://ranto-nyaina.github.io/portofolio/

---

## 🎯 Objectif du site

Un portfolio doit remplir un rôle précis : donner à un recruteur ou un client, en quelques minutes, une vision claire de qui je suis, ce que je sais faire, et ce que j'ai déjà livré.

Ce site répond à ce besoin avec :

* une présentation directe du profil et du positionnement ;
* une cartographie des compétences par domaine (dev, data, réseaux, design) ;
* une sélection de 5 projets concrets, chacun avec une preuve vérifiable (code ou design) ;
* le parcours professionnel et académique ;
* les moyens de contact directs.

Volontairement, le site reste **une page unique, statique, sans framework** — cohérent avec un portfolio qui doit se charger vite et rester simple à maintenir.

---

# 🗂️ Contenu du site

Site statique en une page, structuré en 6 sections :

## 👤 Profil

Présentation et positionnement : développeur full-stack en spécialisation IA et sécurité informatique.

## 🧠 Compétences

Compétences organisées par domaine :

* Développement
* Bases de données
* Systèmes & réseaux
* Data / IA
* Design

## 🚀 Projets

5 réalisations, chacune avec un lien vérifiable vers le code ou le design :

| Projet | Description | Lien |
|---|---|---|
| **Immatriculation fiscale en ligne** | Application mobile pour la Direction Générale des Impôts (réalisée en stage) | [GitHub](https://github.com/Ranto-nyaina/immatriculation_fiscale_en_ligne) |
| **QCM AI** | Génération et correction de QCM assistées par IA | [GitHub](https://github.com/Ranto-nyaina/DevMobile_qcm_IA) |
| **Analyse Big Data des avis clients** | NLP, Machine Learning, PySpark sur un dataset de +560 000 avis clients | [GitHub](https://github.com/Ranto-nyaina/big-data-analyse-avis-clients) |
| **iPark** | Design UI/UX d'une plateforme de location de parkings | [Figma](https://www.figma.com/design/Cm2kS9kLRGap2Itq773dSp/Ipark) |
| **Pare-feu applicatif OWASP ModSecurity** | Configuration d'un WAF sur Kali Linux | — |

## 💼 Expérience

Parcours professionnel.

## 🎓 Formation

Cursus académique.

## 📬 Contact

Email, téléphone, WhatsApp, GitHub, Facebook.

---

# 🛠️ Stack technique

Choix délibérément minimaliste, adapté à un site vitrine statique :

* **HTML / CSS pur** — aucune dépendance JavaScript
* **Police** : IBM Plex Sans / IBM Plex Mono (Google Fonts)
* **Hébergement** : GitHub Pages

Pas de framework, pas de build : le site se déploie tel quel sur GitHub Pages, sans étape de compilation.

---

# 📁 Structure du projet

```text
portofolio/
├── index.html
├── profile.png
└── README.md
```

Structure volontairement plate : un seul fichier HTML, une seule image, pas de dossiers `src/`, `assets/` ou `css/` séparés — cohérent avec la taille réduite du projet, mais à surveiller si le site grandit (voir Perspectives).

---

# 🚀 Installation et lancement en local

Aucune installation nécessaire — deux options :

## Option 1 — Ouverture directe

Ouvrir directement `index.html` dans un navigateur.

## Option 2 — Serveur local

```bash
git clone https://github.com/Ranto-nyaina/portofolio.git
cd portofolio
python -m http.server 8000
```

Puis ouvrir :

```text
http://localhost:8000
```

---

# 🌐 Déploiement

Le site est hébergé et servi directement via **GitHub Pages**, à partir du dépôt :

```text
https://github.com/Ranto-nyaina/portofolio
```

URL publique :

```text
https://ranto-nyaina.github.io/portofolio/
```

Aucune étape de build n'est nécessaire : GitHub Pages sert directement `index.html`.

---

# ⚠️ Limites actuelles

* le WAF OWASP ModSecurity n'a pas de lien de preuve associé (pas de dépôt public), contrairement aux 4 autres projets — à corriger si un dépôt ou une doc existe ;
* un seul fichier HTML pour l'ensemble du site : au-delà d'une certaine taille, la maintenance devient plus difficile sans séparation CSS/JS ;
* pas de version responsive documentée — à vérifier si le rendu mobile est optimisé ;
* pas d'indication de langue (le site est-il en français, anglais, ou bilingue ?) — utile à préciser pour un public international.

---

# 🚀 Perspectives d'amélioration

### Contenu

* ajouter un lien de preuve pour le projet WAF (dépôt de configuration, capture d'écran, ou article technique) ;
* ajouter une version anglaise si le public visé inclut des recruteurs internationaux.

### Technique

* séparer le CSS dans un fichier dédié (`style.css`) si le site continue de grossir ;
* ajouter un fichier `sitemap.xml` et des balises meta pour le référencement (SEO) ;
* ajouter des balises Open Graph pour un meilleur rendu au partage sur les réseaux sociaux.

### Accessibilité

* vérifier le contraste des couleurs et la navigation au clavier ;
* ajouter des attributs `alt` descriptifs sur les images.

---

# 📚 Compétences mises en œuvre

* Développement web statique (HTML / CSS)
* Structuration de contenu et hiérarchisation de l'information
* Déploiement via GitHub Pages
* Communication de projet technique (vulgarisation pour recruteurs)

---

# 📬 Contact

* **Email :** francisco12ranto@gmail.com
* **GitHub :** [@Ranto-nyaina](https://github.com/Ranto-nyaina)

---

# 📌 Conclusion

Ce portfolio réunit en une seule page statique le profil, les compétences et 5 projets vérifiables, du développement mobile à la sécurité informatique en passant par le Big Data et le design UI/UX.

Son intérêt principal n'est pas la sophistication technique du site lui-même — volontairement simple — mais la qualité et la diversité des preuves qu'il pointe : des projets réels, avec du code ou des maquettes accessibles publiquement.
