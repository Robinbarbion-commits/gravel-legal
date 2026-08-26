# Politique de confidentialité — Gravel

**Dernière mise à jour : 26 août 2026**

## Qui est responsable de tes données

Gravel est éditée par **Robin Barbion**, particulier.

Pour toute question ou pour exercer tes droits :
**robinbarbion@icloud.com**

## En résumé

Gravel enregistre ta position pendant tes sorties à vélo, pour tracer ton
parcours et colorer les carrés que tu as parcourus.

Ton tracé GPS n'est visible que par toi. Aucun autre utilisateur ne peut voir
par où tu es passé, ni où sont tes carrés. Tes données ne sont ni vendues, ni
louées, ni transmises à des fins publicitaires.

## Les données que Gravel collecte

**Ta position géographique.** Pendant un enregistrement uniquement, et
seulement après que tu l'aies autorisé. Gravel relève ta latitude, ta
longitude et ton altitude à intervalles réguliers, y compris quand l'écran est
verrouillé et que le téléphone est dans ta poche — sinon la sortie s'arrêterait
au bout de quelques minutes. L'enregistrement s'arrête quand tu appuies sur
Stop. En dehors d'une sortie, Gravel ne relève pas ta position.

**Les informations que tu saisis à l'inscription.** Ton pseudo, ton prénom, ta
date de naissance et le nombre de jours par semaine où tu comptes rouler.

**Ce que tu ajoutes ensuite, si tu le souhaites.** Ta photo de profil, ton
poids et ton poids cible, tes objectifs mensuels.

**Ce que Gravel calcule à partir de tes sorties.** Distance, durée, dénivelé,
vitesse moyenne, carrés parcourus, XP, gemmes, badges et séries.

**Une donnée technique.** Le fuseau horaire de ton téléphone, uniquement pour
envoyer le rappel de série à la bonne heure.

## Pourquoi

| Ce qui est collecté | Pourquoi | Base légale |
|---|---|---|
| Position pendant les sorties | Tracer le parcours et attribuer les carrés — c'est la fonction même de l'app | Exécution du service que tu demandes |
| Pseudo, photo | T'identifier auprès des autres au classement | Exécution du service |
| Prénom | Te saluer dans l'app | Exécution du service |
| Date de naissance | Vérifier l'âge minimum de 15 ans | Obligation légale |
| Jours d'entraînement, objectifs | Calculer tes objectifs mensuels | Exécution du service |
| Poids et poids cible | Suivi personnel et estimation des calories | Ton consentement explicite |
| Fuseau horaire | Envoyer le rappel à l'heure locale | Ton consentement (notifications) |

Le poids et les calories sont des données relatives à la santé. Ils ne sont
jamais collectés d'office : ils n'existent que si tu les renseignes toi-même,
et tu peux les effacer à tout moment.

## Qui peut voir quoi

**Les autres utilisateurs voient :** ton pseudo, ta photo de profil, tes XP et
ta division, et tes totaux au classement — distance cumulée, nombre de
sorties, nombre de carrés, série de flammes.

**Personne d'autre que toi ne voit :** ton tracé GPS, l'emplacement de tes
carrés, ton prénom, ta date de naissance, ton poids et ton poids cible.

Ce n'est pas une promesse déclarative : la base de données elle-même refuse ces
lectures. Chaque table est restreinte à son propriétaire, et le classement lit
des vues qui ne contiennent que les totaux, jamais les coordonnées.

**Le territoire est individuel.** Chaque cycliste a sa propre carte. Dix
personnes qui roulent dans la même rue gagnent chacune ce carré, chez elles.
Personne ne peut prendre le carré de quelqu'un d'autre, ni voir où il se
trouve.

## Les prestataires techniques

**Supabase** héberge la base de données et gère l'authentification.
Sous-traitant au sens du RGPD.

**MapTiler** (ou **CARTO** si aucune clé MapTiler n'est configurée) fournit les
fonds de carte. Quand tu déplaces la carte, ton téléphone leur demande les
tuiles correspondantes : ils reçoivent donc la zone que tu regardes, mais
aucune information sur ton identité, ton compte ou tes sorties.

**Apple** distribue l'application.

Gravel n'utilise aucun outil de mesure d'audience, aucun traceur publicitaire
et aucun réseau publicitaire. Aucune donnée n'est vendue ni partagée à des fins
commerciales.

## Où sont tes données

Sur les serveurs de Supabase. La sortie en cours est aussi écrite temporairement
dans la mémoire de ton téléphone pendant l'enregistrement, pour ne pas la
perdre si l'application se ferme ; ce fichier est effacé dès que la sortie est
enregistrée.

Région d'hébergement : **Irlande** (`eu-west-1`), au sein de l'Union européenne.
Tes données ne sont transférées vers aucun pays hors de l'Union.

## Combien de temps

Tes données sont conservées tant que ton compte existe. Quand tu supprimes ton
compte, elles sont effacées immédiatement et définitivement : profil, sorties,
tracés GPS, territoire, poids, objectifs et amitiés. Il n'existe aucune copie
de sauvegarde permettant de les restaurer.

## Tes droits

Tu peux à tout moment :

- **Accéder** à tes données et en demander une copie
- **Rectifier** ce qui est inexact
- **Supprimer** ton compte et tout ce qui va avec, directement depuis
  l'application (Réglages → Supprimer mon compte)
- **Retirer** l'autorisation de localisation ou de notifications, dans les
  réglages de ton téléphone
- **T'opposer** à un traitement, ou en demander la limitation
- **Demander la portabilité** de tes données

Pour exercer ces droits, écris à **robinbarbion@icloud.com**. Une réponse
te sera apportée sous un mois.

Si tu estimes que tes droits ne sont pas respectés, tu peux saisir la CNIL
(www.cnil.fr).

## Les mineurs

Gravel est accessible à partir de 15 ans, l'âge du consentement numérique en
France. L'inscription est refusée en dessous.

## Modifications

Cette politique peut évoluer. En cas de changement important, tu en seras
informé dans l'application avant que le changement prenne effet.
