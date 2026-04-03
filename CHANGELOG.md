# Changelog - Shxdow Cleanup

## [v3.3] - 2026-04-03

### Added
- Multilang support FR/EN avec sélection au premier lancement.
- Système de traduction via dictionnaire `$Msgs` et variable `$M`.
- Vérification de version Windows (Win10+ requis, guards `$CanTrim` / `$CanPnp`).
- Rapport `.txt` détaillé par module avec gain réel, date et chemin du log.
- Fonction `Load-Config` avec validation des champs et backup auto si corrompu.
- Langue persistée dans `config.json`.

### Fixed
- Regex du switch corrigée (`^O$`, `^1$`...) pour éviter les collisions.
- Rapport en anglais accepte désormais `Y` en plus de `O`.
- `Optimize-Volume` et `Remove-PnpDevice` protégés par guards de version.

---

## [v3.3] - 2026-04-02

### Added
- Fusion complète des commandes v3.1 et v3.2.2.
- Ajout du module Hardware (Intel/Surface).
- Désactivation profonde du VBS et HVCI (FPS Boost).
- Nettoyage des navigateurs Brave et Opera GX.
- Commande ReTrim pour SSD.

### Fixed
- Gestion des erreurs via blocs Try/Catch.
- Problème de persistance des logs.
