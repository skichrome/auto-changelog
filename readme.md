## Git Flow and Auto-Changelog Repository

## Git Flow

### Configuration
Après avoir créé le 1er commit sur le repo git, lancer la configuration de git flow avec `git flow init`.

### Nouvelle fonctionnalité
- Démarrer une nouvelle fonctionnalité avec `git flow feature start XXX`, avec XXX le nom de la fonctionnalité.
- faire des commits en préfixant chaque nouvelle modification importante avec `feat:` et chaque petite modification avec `fix:`.
- Une fois la fonctionnalité terminée, exécuter `git flow feature finish XXX`, avec XXX le nom de la fonctionnalité correspondante.