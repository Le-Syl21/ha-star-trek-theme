# Star Trek Theme for Home Assistant

![Star Trek Theme](https://img.shields.io/badge/Home%20Assistant-Theme-blue.svg)
![HACS](https://img.shields.io/badge/HACS-Compatible-green.svg)
![License](https://img.shields.io/badge/License-GPLv3-yellow.svg)

Un thème Home Assistant avec les couleurs authentiques LCARS de Star Trek. Installation automatique via HACS !

## 🖼️ Aperçu

![Star Trek LCARS Theme Colors](https://via.placeholder.com/800x400/000000/FF9900?text=🖖+STAR+TREK+THEME+COLORS)

*Couleurs LCARS authentiques : Orange (#FF9900), Jaune (#FFCC00), Bleu (#0099CC)*

## ✨ Caractéristiques

- 🟠 **Couleurs LCARS officielles** : Orange, Jaune, Bleu comme dans Star Trek
- 🖤 **Arrière-plan spatial** : Noir profond pour l'immersion
- 🎨 **Compatibilité complète** : Tous les composants Home Assistant
- 📱 **Responsive** : Desktop et mobile
- ⚡ **Installation simple** : 1 clic via HACS

## 🚀 Installation

### Via HACS (Recommandé)
1. ✅ **HACS** → **Frontend** → **Themes**
2. ✅ **Recherchez** "Star Trek Theme"
3. ✅ **Installez** le thème
4. ✅ **Redémarrez** Home Assistant
5. ✅ **Activez** dans Profil → Thème → "star-trek"

### Installation manuelle
1. Téléchargez `star-trek.yaml`
2. Placez dans `/config/themes/`
3. Ajoutez dans `configuration.yaml` :
```yaml
frontend:
  themes: !include_dir_merge_named themes/
```
4. Redémarrez Home Assistant

## 🎨 Palette de couleurs

| Couleur | Code Hex | Usage LCARS |
|---------|----------|-------------|
| Orange Principal | `#FF9900` | Éléments principaux, navigation |
| Jaune Accent | `#FFCC00` | États actifs, sélections |
| Bleu Information | `#0099CC` | Messages informatifs |
| Rouge Alerte | `#CC0000` | Erreurs et alertes |
| Noir Spatial | `#000000` | Arrière-plan principal |

## 🖖 Complément recommandé

Pour une expérience LCARS complète avec les formes géométriques authentiques, installez aussi :

**[Star Trek LCARS Plugin](https://github.com/Le-Syl21/ha-star-trek-plugin)**
- Formes géométriques asymétriques
- Bordures colorées sur les cartes
- Police futuriste Orbitron
- Animations LCARS

```
Installation : HACS → Frontend → Plugins → "Star Trek LCARS Plugin"
```

## 🔄 Utilisation avec le plugin

1. **Installez ce thème** (couleurs de base)
2. **Installez le plugin** (formes géométriques)
3. **Activez le thème** "star-trek"
4. **Profitez** de l'interface LCARS complète ! 🚀

## 🤝 Contribution

Les contributions sont les bienvenues !

1. Fork le projet
2. Créez votre branche (`git checkout -b feature/amelioration`)
3. Committez (`git commit -am 'Ajout fonctionnalité'`)
4. Push (`git push origin feature/amelioration`)
5. Ouvrez une Pull Request

## 📝 Changelog

### v1.0.0
- Couleurs LCARS authentiques
- Support complet Home Assistant
- Installation automatique HACS

## 📄 Licence

GPLv3 - Voir [LICENSE](LICENSE)

## 🖖 Remerciements

- Inspiré par l'interface LCARS de Michael Okuda
- Communauté Home Assistant
- Live long and prosper! 🖖

---

**Note** : Non affilié à CBS/Paramount. Star Trek est une marque déposée.
