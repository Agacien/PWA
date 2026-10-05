<H1>Projets PWA</H1>

On trouve ici plusieurs applications :
<BR>.
Editeur de visite
<BR>.
<H2><B>editpoih</B></H2><BR>
<A HREF="https://agacien.github.io/PWA/editpoih/">editpoih</A>
<BR>
Cet éditeur de visite est le plus avancé des projets de ce genre
<HR>

______________________________________________________________________

Visualiseur de visite<BR>
<H2><B>visupoicd</B></H2><BR>
<A HREF="https://agacien.github.io/PWA/visupoicd/">visupoicd</A>
<BR>Le plus avancé des guides de visite
<BR>Fonctionne bien avec l'éditeur editpoih, avec en plus une lightbox (un clic sur l'image ouvre une lightbox zoomable)

________________________________
<p>&nbsp;Les POI (Points Of Interest) ou Points d'intérêt sont les petits "cailloux blancs" qu'on laisse sur un trajet pour se souvenir, bien après, de certains lieux marquants.</p><p>Ce trajet peut être une excursion touristique ou géologique, une randonnée pédestre, la visite d'un musée.<br /><br />Une visite est un ensemble structuré de POIs.</p><p>Un POI comporte ou peut comporter différents objets :</p><p></p><ul style="text-align: left;"><li>un ID ou identificateur</li><li>un titre (obligatoire)</li><li>une géolocalisation GPS (obligatoire)</li><li>un commentaire textuel (facultatif)</li><li>une image ou une photo (facultatif)</li><li>un commentaire audio (facultatif)</li><li>une vidéo (facultative).</li></ul><div>Puisqu'il est obligatoirement géolocalisé, chaque POI d'une visite peut être représenté par un marqueur sur un fond de carte. Par exemple, une épingle sur un fond de carte Open Street Map.</div><div><br /></div><div>Il y a deux aspects dans une visite :</div><div><ul style="text-align: left;"><li>sa construction</li><li>sa visualisation<br /><br /></li></ul><div><b>Construire une visite</b> consiste à décrire une succession de POIs, en fournissant pour chaque POI le maximum des objets qu'on vient de nommer. On peut par exemple choisir une photo ou une vidéo captée avec son smartphone,ou encore enregistrer un commentaire vocal descriptif du POI.</div></div><div><br /></div><div><b>Visualiser une visite</b> consiste à suivre des POIs sur une carte. Cette carte, de manière élémentaire, peut être une carte OSM (OpenStreet Map) sur laquelle les POIs sont représentés par des marqueurs. Un clic sur ces marqueurs entraîne l'ouverture de popups (petites fenêtres flottantes) montant les données attachées au POI.<br />La visualisation des POIs peut se faire dans deux situations :</div><div><span>&nbsp; &nbsp; - en chambre, avec un ordinateur, c'est une visite virtuelle,</span><br /></div><div><span><span>&nbsp; &nbsp; - sur le terrain, avec un smartphone géolocalisé, c'est une visite guidée.</span><br /></span></div><div><span><span><br /></span></span></div><div><span><span>Entre la construction et la visualisation se fait un passage de données, par le truchement d'un fichier.<br />Ce fichier est en fait une archive (un zip) qui comporte les données brutes&nbsp; (dossier "data") et la structure qui lie les données (fichier visit.json).</span></span></div><div><span><span><br /></span></span></div><div><span><span>La traduction informatique de cette visite guidée va être réalisée par l'écriture de plusieurs applications qui ont en commun le fait d'être des PWA (Progressive Web Applications). Rappelons en quelques phrases l'intérêt du choix des PWA.</span></span></div><div><span><span><span>&nbsp; &nbsp; -&nbsp;</span></span></span><b>Code unique :</b> Une PWA utilise une seule base de code (HTML, CSS, JavaScript) pour toutes les plateformes (web, mobile, desktop).<br /><span>&nbsp; &nbsp; -&nbsp;</span><b>Pas de store d'applications obligatoire :</b> L'utilisateur peut installer la PWA directement depuis le navigateur, sans passer par l'App Store ou Google Play, simplifiant le processus d'adoption.<br /><span>&nbsp; &nbsp; -&nbsp;</span><b>Légèreté :</b> Les PWA sont souvent beaucoup plus légères que les applications natives.</div><div><span>&nbsp; &nbsp; -&nbsp;</span><b>Vitesse et performance :</b> Les PWA sont conçues pour être rapides et réactives.<br /><span>&nbsp; &nbsp; -&nbsp;</span><b>Fonctionnement hors ligne (ou avec connexion limitée) :</b> Grâce aux <i>Service Workers</i>, elles peuvent mettre en cache du contenu et fonctionner même sans connexion Internet ou avec une connexion instable.</div><div><span>&nbsp; &nbsp; -&nbsp;</span><b>Partage facilité :</b> Elles peuvent être lancées et partagées via un simple lien URL.</div><div><br /></div><div>Pour bâtir les applications, les robots générateurs de code sont essentiels (ChatGPT, Claude, Gemini, Grok, Github Copilot, Perplexity ...). Leur rôle a été déterminant.</div><div><br /></div><div>La construction de la visite à partir des POIs est basée sur 3 applications accessibles sur le dépôt Github :<br /><span>&nbsp; &nbsp;<span style="font-size: medium;"> - <a href="https://bernardhoyez.github.io/PWA/editpoih/" target="_blank">editpoih</a>&nbsp;: construction des POI</span></span></div><div><span><span style="font-size: medium;">&nbsp; &nbsp; - <a href="https://bernardhoyez.github.io/PWA/modifpoi/" target="_blank">modifpoi</a>&nbsp;: correction et déplacement des POIs</span></span></div><div><span><span style="font-size: medium;">&nbsp; &nbsp; - <a href="https://bernardhoyez.github.io/PWA/ordonnepoi/" target="_blank">ordonnepoi</a>&nbsp;: tri les POI selon la latitude ou la longitude</span></span></div><div><br />La visualisation de la visite est réalisée par :</div><div><span>&nbsp; &nbsp;<span style="font-size: medium;"> - <a href="https://bernardhoyez.github.io/PWA/visupoicd/" target="_blank">visupoicd</a>&nbsp;: visite virtuelle ou visite guidée</span></span><br /></div><div><span><br /></span></div><div><span>Une fois que l'application est lancée dans le navigateur (Chrome, Firefox, Safari ...), il est possible de l'installer. Selon le navigateur et le type de plateforme, le processus d'installation est différent. Il peut s'agir d'une icône particulière à côté de la barre d'URL ou d'une option accessible par l'icône "trois points" ou hamburger. L'application apparaît avec son icône sur la page d'accueil et dans la liste des applications installées.</span></div><div><span><br /></span></div><div>Comment utiliser&nbsp;<a href="https://bernardhoyez.github.io/PWA/editpoih/" style="font-size: large;" target="_blank">editpoih</a></div><div>1) Donner un nom à la visite renfermant les POIs.</div><div>Remarquer tout de suite qu'il est possible de reprendre une visite déjà commencée et pour laquelle on ajoute des POIs supplémentaire. Cette visite préliminaire est un fichier .zip.</div><div>2) Donner un titre au POI sur lequel on va travailler.</div><div>3) Deux champs d'entrée qui permettent de fixer la latitude et la longitude du POI. Ces champs peuvent être remplis de 3 manières :</div><div><span>&nbsp; &nbsp; - automatiquement par importation d'une photogéolocalisée (métadonnées EXIF)</span><br /></div><div><span><span>&nbsp; &nbsp; - par positionnement manuel d'un marqueur sur la carte OSM</span><br /></span></div><div><span><span><span>&nbsp; &nbsp; - par remplissage manuel (format degrés décimaux, avec point décimal).</span><br /></span></span></div><div>La géolocalisation est obligatoire de quelque manière que ce soit.</div><div>4) Remplissage d'un commentaire textuel.</div><div>5) Importation d'un fichier audio MP3.</div><div>6) Importation d'une vidéo MP4</div><div>7) Quand toutes les données sont introduites, on clique sur le bouton "Ajouter ce POI".</div><div>Ce POI apparaît alors dans la liste des POIs validés, dans la colonne de droite.</div><div>8) On recommence avec l'introduction d'un nouveau POI, autant de fois qu'il y a de POIs prévus.<br />9) Quand&nbsp; tous les POIs sont validés, on sauvegarde la visite sous la forme d'un fichier Zip.</div><div><br /></div><div>Les POIs apparaissent dans la liste dans l'ordre dans lequel ils ont été introduits.</div><div>Par glisser/déposer, on peut modifier cet ordre.<br />On peut également éditer de nouveau un POI de la liste ou le supprimer.</div><div><br /></div><div>Comment utiliser&nbsp;<a href="https://bernardhoyez.github.io/PWA/modifpoi/" style="font-size: large;" target="_blank">modifpoi</a></div><div>Il est fréquent qu'une photo ait été mal géolocalisée par le GPS inetrne du smartphone. Le marqueur du POI se trouve positionné sur la carte au maivais endroit.</div><div>A l'aide de la carte, on déplace le marqueut fautif au bon enfroit. On sauvegarde le fichier modifié.</div><div><br /></div><div>Comment utiliser&nbsp;<a href="https://bernardhoyez.github.io/PWA/ordonnepoi/" style="font-size: large;" target="_blank">ordonnepoi</a></div><div>Les POIs sont souvent entrés dans un ordre indifférent à leur ordonnancement géographique.<br />Si la visite est linéaire, il est possible de réorganiser les POIs selon la latitude ou selon la longitude.<br />Comme les marqueurs sont numérotés, il est alors plus facile de suivre la progression sur le terrain.</div><div><br /></div><div>Comment utiliser&nbsp;<a href="https://bernardhoyez.github.io/PWA/visupoicd/" style="font-size: large;" target="_blank">visupoicd</a></div><div><br /></div><div>Alors que la construction des POIs se prépare essentiellement sur Desktop (ordinateur), la visualisation des POIs est intrinséquement plus adaptée aux situations de mobilité externe et donc au smartphone. Visupoicd peut fonctionner sur PC ou sur Mac, mais on reste dans la virtualité.</div><div>On insistera donc sur les propriétés de l'application installée sur un smartphone (Android ou iOS).</div><div><br /></div><div>A l'ouverture de l'application, il n'est demandé que de charger un fichier .zip.</div><div>Ce fichier .zip qui peut atteindre des dizaines ou des centaines de mégaoctets aura été précédemment sauvegardé dans un dossier facilement accessible. Sa taille interdit généralement d'être transmis par mél. On utilisera à cet effet des plateformes de transfert de fichiers lourds ou un Drive dans le cloud.</div><div>Si la visite comporte de nombreux POIs et des fichiers média lourds, alors l'importation peut demander un certain temps.</div><div><br /></div><div>Une carte s'affiche présentant une suite numérotée de marqueurs de POIs. Normalement, tous les POIs sont représentés et correspondent à une certaine échelle. Il est possible de zoomer pour grossir et mieux distinguer individuellement les POIs..</div><div>Un clic sur un marqueur de POI enttraîne l'ouverture d'une popup (petite fenêtre attachée au point).</div><div>Si vous déplacez la carte (glisser), vous constatez que votre position géographique actuelle est figurée par un gros marqueur rouge pulsant. En zoomant dessus, vous verrez les détails de topographie ou d'architecture apparaître.</div><div>Dans la popup sont figurés :</div><div><span>&nbsp; &nbsp; - le titre du POI,</span><br /></div><div><span><span>&nbsp; &nbsp; - sa latitude et sa longitude</span><br /></span></div><div><span><span><span>&nbsp; &nbsp; - un commentaire (facultatif)</span><br /></span></span></div><div><span><span><span>&nbsp; &nbsp; - une photo (facultative)</span><br /></span></span></div><div><span><span><span><span>&nbsp; &nbsp; - un lecteur audio (facultatif)</span><br /></span></span></span></div><div><span>&nbsp; &nbsp; - un lecteur vidéo (facultatif)</span><br /></div><div><span><span>&nbsp; &nbsp; - une distance en mètres vous séparant du POI</span><br /></span></div><div><span><span><span>&nbsp; &nbsp; - un azimut en degrés par rapport au Nord vers le POI sélectionné.<br /></span>La distance et l'azimut sont mis à jour à mesure que vous vous déplacez. On peut ainsi se rapprocher progressivement du POI en tenant compte de l'évolution de la distance.</span></span></div><div><span><span><span><br /></span></span></span></div><div><span><span><span>Si une photo est présente dans la popup, un simple clic sur cette photo ouvre une "lightbox" zoomable.</span></span></span></div><div><span><span><span>Ceci permet d'observer des détails précis à l'intérieur de la photo. Une croix de fermeture permet de faire disparaître la lightbox.</span></span></span></div><div><span><span><span><br /></span></span></span></div><div><br /></div><div><br /></div><p></p>
___________________________________________________________


# traceY

> Convertisseur GPX/KML vers carte HTML interactive

![PWA](https://img.shields.io/badge/PWA-Ready-success)
![Offline](https://img.shields.io/badge/Offline-Compatible-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 🎯 Description

**traceY** est une Progressive Web App (PWA) qui convertit vos fichiers de traces GPS (GPX ou KML) en cartes HTML interactives autonomes. 

L'application fonctionne entièrement dans votre navigateur - aucune donnée n'est envoyée à un serveur externe.

## ✨ Fonctionnalités

- 📁 **Drag & Drop** : Glissez-déposez vos fichiers directement
- 🗺️ **Carte interactive** : Visualisation avec Leaflet et OpenStreetMap
- 💾 **Export multiple** : Téléchargez en GPX, KML ou GeoJSON
- 📱 **PWA installable** : Utilisable hors ligne après installation
- 🔒 **100% local** : Vos données restent sur votre appareil
- 🚀 **Zéro configuration** : Prêt à l'emploi

## 🚀 Utilisation

### En ligne

Accédez à l'application : [https://agacien.github.io/PWA/traceY/](https://BernardHoyez.github.io/PWA/traceY/)

### Étapes

1. **Glissez-déposez** un fichier `.gpx` ou `.kml` dans la zone prévue
   - Ou cliquez sur la zone pour sélectionner un fichier
2. **Attendez** la conversion (quelques secondes)
3. **Téléchargez** automatiquement le fichier HTML généré
4. **Ouvrez** le fichier HTML dans n'importe quel navigateur

### Le fichier HTML généré

Le fichier HTML résultant contient :
- ✅ Votre tracé GPS (embarqué en GeoJSON)
- ✅ Une carte interactive Leaflet
- ✅ Des boutons pour exporter vers GPX, KML ou GeoJSON
- ⚠️ Nécessite une connexion internet pour afficher le fond de carte OpenStreetMap

## 📦 Installation locale

### Prérequis

Aucun ! Tout fonctionne dans le navigateur.

### Installation comme PWA

1. Ouvrez l'application dans Chrome, Edge ou Safari
2. Cliquez sur l'icône d'installation dans la barre d'adresse
3. L'application sera disponible hors ligne sur votre appareil

### Développement local

```bash
# Cloner le dépôt
git clone https://github.com/BernardHoyez/BernardHoyez.github.io.git

# Naviguer vers le dossier
cd BernardHoyez.github.io/PWA/traceY

# Lancer un serveur local (exemple avec Python)
python -m http.server 8000

# Ouvrir dans le navigateur
# http://localhost:8000
```

## 📁 Structure du projet

```
traceY/
├── index.html          # Interface principale
├── app.js              # Logique de l'application
├── sw.js               # Service Worker (mode offline)
├── manifest.json       # Configuration PWA
├── icon192.png         # Icône 192x192
└── icon512.png         # Icône 512x512
```

## 🛠️ Technologies

- **Vanilla JavaScript** : Aucun framework requis
- **Leaflet** : Bibliothèque de cartographie interactive
- **toGeoJSON** : Conversion GPX/KML → GeoJSON
- **togpx** : Conversion GeoJSON → GPX
- **tokml** : Conversion GeoJSON → KML
- **Service Worker** : Fonctionnement hors ligne

## 🌐 Compatibilité

| Navigateur | Version minimum | Support |
|------------|-----------------|---------|
| Chrome     | 67+             | ✅ Complet |
| Firefox    | 63+             | ✅ Complet |
| Safari     | 11.1+           | ✅ Complet |
| Edge       | 79+             | ✅ Complet |

## 📝 Formats supportés

### En entrée
- `.gpx` - GPS Exchange Format
- `.kml` - Keyhole Markup Language

### En sortie (depuis le HTML généré)
- `.gpx` - GPS Exchange Format
- `.kml` - Keyhole Markup Language  
- `.geojson` - GeoJSON

## 🔐 Confidentialité

- ✅ Aucune donnée n'est envoyée à un serveur
- ✅ Traitement 100% local dans le navigateur
- ✅ Aucun cookie, aucun tracking
- ✅ Vos fichiers GPS restent privés

## ⚠️ Limitations actuelles

- Le HTML généré nécessite internet pour le fond de carte OSM
- Les fichiers très volumineux (>10 MB) peuvent être lents à traiter
- Le Service Worker nécessite HTTPS (sauf localhost)

## 🚧 Améliorations futures

- [ ] Support des fichiers `.mbtiles` pour fonctionnement 100% offline
- [ ] Personnalisation de la couleur du tracé
- [ ] Support des waypoints et POI
- [ ] Statistiques de la trace (distance, dénivelé)
- [ ] Fusion de plusieurs traces

## 🤝 Contribution

Les contributions sont les bienvenues !

1. Fork le projet
2. Créez une branche (`git checkout -b feature/amelioration`)
3. Committez vos changements (`git commit -am 'Ajout fonctionnalité'`)
4. Poussez vers la branche (`git push origin feature/amelioration`)
5. Ouvrez une Pull Request

## 📄 Licence

MIT License - voir le fichier LICENSE pour plus de détails

## 👤 Auteur

**Bernard Hoyez**

- GitHub: [@BernardHoyez](https://github.com/BernardHoyez)

## 🙏 Remerciements

- [Leaflet](https://leafletjs.com/) - Bibliothèque de cartographie
- [OpenStreetMap](https://www.openstreetmap.org/) - Données cartographiques
- [Mapbox](https://github.com/mapbox/togeojson) - Bibliothèque toGeoJSON
- Communauté open source

---

⭐ Si vous trouvez ce projet utile, n'hésitez pas à lui donner une étoile !

