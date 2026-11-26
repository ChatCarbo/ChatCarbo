### Responsable d'études · Logiciels libres en Rust & Python, pilotés par l'IA

Je travaille dans l'industrie, sur des études techniques et de la recherche de pannes. Je suis autodidacte en informatique. Sur ce compte, je publie des logiciels libres et locaux que je conçois et que je teste moi-même ; **le code est écrit par des modèles d'IA sous ma direction**.

Mon rôle sur chaque projet : définir le besoin, écrire la spécification, relire et orienter le code produit, tester sous Windows, puis corriger et publier.

#### Projets

| Projet | Ce qu'il fait | Statut |
|---|---|---|
| [**Escarcelle**](https://github.com/ChatCarbo/Escarcelle) 🆕 | Suivi local de l'épargne : livrets réglementés (intérêts par quinzaine, meilleur moment pour verser ou retirer) et PEA (cours automatiques, plus-values, dividendes nets, alertes, analyse technique) ; en préparation : import des relevés (BoursoBank, Fortuneo, Moning) et sauvegarde chiffrée | v0.3 publiée, 0.4 en cours ; spécification publiée, 160+ tests dont 600 scénarios de livrets vérifiés par un calcul indépendant, intégration continue |
| [**PlotFlora**](https://github.com/ChatCarbo/plotflora) | Planification de jardin sur vue aérienne IGN ou plan dessiné : massifs, haies, plantes isolées, et un algorithme explicable qui classe les plantes adaptées sur 100 points et calcule les quantités | v1.2 (détection du contour du jardin, ambiances, mode d'emploi), spécification publiée, 35+ tests unitaires |
| [**Kip**](https://github.com/ChatCarbo/Kip) | Gestionnaire de mots de passe local : Argon2id + XChaCha20-Poly1305, verrouillage automatique, import CSV / Bitwarden / KeePassXC | Le plus abouti, 150+ tests unitaires |

#### Ma méthode

1. **Cadrage** : partir d'un besoin réel et le traduire en spécification.
2. **Développement assisté** : faire produire le code par l'IA, le relire, imposer les choix d'architecture et de sécurité.
3. **Recette** : tester moi-même sous Windows, y compris les cas limites.
4. **Livraison** : corriger, documenter (README, CHANGES) et publier une version.

**Prochaines étapes :** étendre l'intégration continue (fmt, clippy, tests), déjà en place sur Escarcelle, à tous les dépôts, et vérifier les calculs d'Escarcelle sur de vrais relevés.

**Outils :** Rust (egui, iced, Tauri), Svelte, SQLite, Python, Git, PowerShell, Notepad++, Windows.

---

<details>
<summary><b>English</b></summary>

### Study Manager · AI-driven free software in Rust & Python

I work in industry on technical studies and troubleshooting, and I am self-taught in computer science. On this account I publish free, local-first software that I design and test myself; **the code is written by AI models under my direction**.

My role on each project: define the need, write the specification, review and steer the generated code, test on Windows, then fix and release.

- **[Escarcelle](https://github.com/ChatCarbo/Escarcelle)** (new, v0.3 released, 0.4 in progress): local savings tracker for French regulated savings accounts and PEA, with automatic quotes, net dividends, alerts and technical analysis; statement import and encrypted backup coming in 0.4. Specification published, 160+ tests including 600 generated scenarios checked against an independent calculation, continuous integration.
- **[PlotFlora](https://github.com/ChatCarbo/plotflora)** (v1.2): garden planner on IGN aerial imagery or a drawn plan, with an explainable 100-point plant suitability score; specification published.
- **[Kip](https://github.com/ChatCarbo/Kip)**: local password manager (Argon2id + XChaCha20-Poly1305), my most mature project, 150+ unit tests.

**Next:** extend CI (already on Escarcelle) to every repo, and check Escarcelle's figures against real bank statements.

</details>
