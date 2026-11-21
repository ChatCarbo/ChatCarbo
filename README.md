### Responsable d'études · Outils Windows en Rust & Python, pilotés par l'IA

Je travaille dans l'industrie, sur des études techniques et de la recherche de pannes. Je suis autodidacte en informatique. Sur ce compte, je publie des utilitaires Windows que je conçois et que je teste moi-même ; **le code est écrit par des modèles d'IA sous ma direction**.

Mon rôle sur chaque projet : définir le besoin, écrire la spécification, relire et orienter le code produit, tester sous Windows, puis corriger et publier.

#### Projets

| Projet | Ce qu'il fait | Statut |
|---|---|---|
| [**Kip**](https://github.com/ChatCarbo/Kip) | Gestionnaire de mots de passe local : Argon2id + XChaCha20-Poly1305, verrouillage automatique, import CSV / Bitwarden / KeePassXC | Le plus abouti, 150+ tests unitaires |
| [**FLX Archiver**](https://github.com/ChatCarbo/flx-archiver) | Archiveur ZIP, 7z, Zstd, Gzip (extraction RAR), qui recommande un format selon le contenu | Utilisable, peu de tests |
| [**MemGuard**](https://github.com/ChatCarbo/Memguard) | Moniteur de RAM et allègement ciblé des processus en arrière-plan | Utilisable, sans tests |
| [**Razdisk**](https://github.com/ChatCarbo/Razdisk) | Formateur de clés USB et cartes SD (diskpart + format), FAT32 sans limite de taille | En cours de correction, à utiliser avec prudence |
| [**RGPD Cleaner**](https://github.com/ChatCarbo/rgpd-cleaner) | Retrouve les comptes liés à une adresse e-mail et prépare les demandes d'effacement (article 17 du RGPD) | Prototype |

#### Ma méthode

1. **Cadrage** : partir d'un besoin réel et le traduire en spécification.
2. **Développement assisté** : faire produire le code par l'IA, le relire, imposer les choix d'architecture et de sécurité.
3. **Recette** : tester moi-même sous Windows, y compris les cas limites.
4. **Livraison** : corriger, documenter (README, CHANGES) et publier une version.

**Prochaines étapes :** intégration continue (fmt, clippy, tests) sur tous les dépôts, plus de tests automatisés, et des spécifications publiées dans chaque projet.

**Outils :** Rust (egui, iced), Python, Git, PowerShell, Notepad++, Windows.

---

<details>
<summary><b>English</b></summary>

### Study Manager · AI-driven Windows tools in Rust & Python

I work in industry on technical studies and troubleshooting, and I am self-taught in computer science. On this account I publish Windows utilities that I design and test myself; **the code is written by AI models under my direction**.

My role on each project: define the need, write the specification, review and steer the generated code, test on Windows, then fix and release.

- **[Kip](https://github.com/ChatCarbo/Kip)**: local password manager (Argon2id + XChaCha20-Poly1305), my most mature project, 150+ unit tests.
- **[FLX Archiver](https://github.com/ChatCarbo/flx-archiver)**: ZIP / 7z / Zstd / Gzip archiver with format recommendation.
- **[MemGuard](https://github.com/ChatCarbo/Memguard)**: RAM monitor with targeted background-process trimming.
- **[Razdisk](https://github.com/ChatCarbo/Razdisk)**: USB / SD card formatter (being fixed, use with care).
- **[RGPD Cleaner](https://github.com/ChatCarbo/rgpd-cleaner)**: finds accounts linked to an email and drafts GDPR erasure requests (prototype).

**Next:** CI on every repo, more automated tests, published specs.

</details>
