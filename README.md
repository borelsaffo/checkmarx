# checkmarx

# 🛡️ Checkmarx – Sécurité des applications (AppSec)

## 🧭 C’est quoi ?
**Checkmarx** est une **plateforme de sécurité applicative** conçue pour **identifier les vulnérabilités dans le code source, les dépendances, l’infrastructure-as-code (IaC), et plus encore**, tout au long du cycle de développement logiciel.

---

## 🧰 Fonctions principales

### 🔍 1. SAST – Static Application Security Testing
- Analyse **le code source** pour identifier les failles de sécurité (ex: injections, XSS, mauvaise gestion des accès...).
- Supporte plusieurs langages (Java, C#, JavaScript, Python, etc.).
- Très utile **dès le début du développement**.

### 🧱 2. SCA – Software Composition Analysis
- Scanne les **dépendances open source** pour détecter :
  - Vulnérabilités connues (CVE)
  - Licences problématiques
- Aide à gérer les **risques liés à l’open source**.

### ☁️ 3. IaC Security
- Analyse les fichiers **Terraform, CloudFormation, etc.**
- Cherche des erreurs de configuration (ex: ports ouverts, droits excessifs…).

### 🔗 4. API Security
- Analyse de la sécurité des **API exposées** dans ton code.
- Détection de failles comme l’exposition de données sensibles ou le manque de contrôle d’accès.

### ⚙️ 5. CI/CD Integration
- Intégration facile dans des pipelines DevOps :
  - Jenkins, GitLab, GitHub Actions, Azure DevOps, etc.
- Possibilité de bloquer un build si des failles critiques sont détectées.

---

## ✅ Avantages

- **Très bon support multilangue**
- **Rapports clairs et exploitables**
- **Très adapté aux environnements DevSecOps**
- Analyse **deep scan** du code avec **peu de faux positifs**
- **Interface web intuitive**
- Modules spécialisés pour couvrir **tous les aspects AppSec**

---

## ❌ Inconvénients possibles

- Peut être **coûteux** pour les petites équipes.
- Configuration initiale **assez technique**.
- Analyse SAST parfois **lente sur de très gros projets**.

---

## 🧠 En résumé

| Fonction        | Objectif                       | Avantage                                       |
|------------------|-------------------------------|------------------------------------------------|
| SAST            | Analyse du code source         | Trouver des vulnérabilités avant exécution     |
| SCA             | Analyse open source            | Gérer les CVEs et les licences                 |
| IaC Security    | Sécurité Cloud                 | Éviter les erreurs de config dans le code infra|
| API Security    | Test des API exposées          | Détection des fuites et failles dans les endpoints |
| CI/CD           | Intégration continue           | Automatisation dans le pipeline DevOps         |

---
 **Checkmarx** ou (comme SonarQube, Veracode, Snyk) pour la sécurité applicative
