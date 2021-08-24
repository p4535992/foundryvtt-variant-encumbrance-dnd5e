


### Update 0.4.5

- Revert url repository form p4535992 to VanirDev and fix the module.json
### Update 0.4.4

- Some minor bug fix,
- Applied prettier

### Update 0.4.3

- Bug fix make sure to remove active effect if you rename the active effect
### Update 0.4.2

- Add more i18n support

### Update 0.4.1

- BUg fixing euiped and unequiped listener

### Update 0.4.0

- Bug fix compatibility with invenotry + module
- Bug fix unequipped mutliplier set 0 still get weight and broke encumbrance calculation

### Update 0.3.9

- Stupid , Stupid bug
- Clean up code
- Add check for active effect present when ecumerance leevel not change

### Update 0.3.8

- Add implementation with the core foundry 0.8.8 and D&D5e 1.4.2 for encumbrance rule

### Update 0.3.7

- Many bug fix and updates
- Finally integration with Active effects for encumbrance
  
### Update 0.3.6

- Many bug fix and updates

### Update 0.3.5

- Converted to typescript (because i iike it better than javascript) and some bug fix
  
### Update 0.3.4

* Update for 0.8.8
* Add internazionalization
* Add fix from [hmqgg fork](https://github.com/hmqgg/VariantEncumbrance/commit/27004558654bbd28eeb419c35d8f88093fbb7605)
* Add optional use of the module midi (if the module is installed or not) request from tgp (unkwnon discord name)
* Minor bug fix
  
### Update 0.3.3
  
* Bugfixes for foundryvtt 0.8.6
* Setup npm for better build the project in the future
  
### Update 0.3.2
  
* Bugfixes for inventory+ support
* Added support for Dynamic Active Effects

### Update 0.3

* Complete support for the Inventory+ mod
* Major bugfixes for the effects-based system involving unwanted stacked effects, and permission errors. Major thanks to [Paul Lessing](https://github.com/paullessing) for his contributions here.
* Support for custom units and speed decreases in the module settings.
* Improved weight calculation to support active effects that affect the data.attributes.encumbrance.value value.

### Update 0.2

* [Reworked weight reduction to use the new Active Effects system.](#ActiveEffects)
* Refactored weight calculations to happen on inventory update, instead of only re-calculating weight when opening the character sheet.

### Update 0.1.5

* Added weight multiplier for unequipped items

### Update 0.1.4

* Support for Tidy5e dark theme character sheet
* [Improved weight calculations to support creature size and powerful build](#sizeAndBuild)
* [Added flags to support 3rd party module integration](#variantFlags)