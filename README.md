# MMIAtelier — Atelier MMI : ordres de fabrication, planning et suivi d'atelier.

> Module Dolibarr **MMIAtelier** (version 1.0), branche `20.0`.

## Fonctionnalités

### Fonctionnalités principales

- Ordres de fabrication, planning et suivi des postes.
- Menus et configuration atelier.

### Pages

- `admin/about.php`
- `admin/setup.php`
- `mmiatelierindex.php`

### Configuration

| Constante | Type | Rôle |
|---|---|---|
| `MMIATELIER_MYPARAM1` | string | My param 1 |
| `MMIATELIER_MYPARAM2` | textarea | My param 2 |
| `MMIATELIER_MYPARAM3` | category: |  |
| `MMIATELIER_MYPARAM4` | emailtemplate:thirdparty |  |
| `MMIATELIER_MYPARAM5` | yesno |  |
| `MMIATELIER_MYPARAM6` | securekey |  |
| `MMIATELIER_MYPARAM7` | product |  |

### Classes et composants

- `lib/mmiatelier.lib.php`

## Prérequis

- Dolibarr >= 11.0 (branche `20.0` : Dolibarr 20.0).
- Modules MMI : `mmicommon`. **`mmicommon` doit être activé en premier.**

## Installation

1. Copier le module dans `htdocs/custom/mmiatelier` :

   ```sh
   cd htdocs/custom
   git clone <dépôt> mmiatelier
   ```

2. Dans Dolibarr : **Configuration → Modules**, activer d'abord `mmicommon`, puis ce module.
3. Vérifier les permissions dans la fiche des utilisateurs concernés.

## Licence

GPLv3 ou ultérieure — voir `COPYING`. Documentation sous GFDL.

## Changelog

Voir [CHANGELOG.md](CHANGELOG.md) (évolutions datées).
