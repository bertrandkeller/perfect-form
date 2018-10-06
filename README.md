# Le formulaire parfait

Il s'agit d’un atelier ouvert durant lequel les personnes peuvent venir travailler seul ou en équipe. Le but est d'échanger ensemble sur le sujet des formulaires.

Aujourd'hui les besoins concernant peuvent être multiples : contacts, commentaires, consultations… Il est possible de l’intégrer grâce des applications ou des CMS, mais aussi grâce à des solutions ou des services tiers.

Construisons ensemble des cas pratiques d'usage (j'en ai déjà un certain nombre) et voyons comment maximiser la validation en utilisant au maximum les (nouvelles) propriétés HTML et CSS, le contrôle de champs (CSS ou JS), le retour d'information, la déconnexion…

L'objectif de cet atelier est de construire une ou plusieurs notices sur la manière de réaliser le « formulaire parfait » et mettre en ligne les exemples réalisés lors de l'atelier.

## Objectifs

  1. Travailler en groupe
  2. Tour d’horizon de la manière d’écrire un formulaire
  3. Écrire des modules d’exemple de formulaires
  4. Les partager sur un dépôt

## Déroulé

  1. Mise en place
  2. Séance 1
  3. Revue
  4. Séance 2
  5. Rendu

### Mise en place

- Constitution des groupes
- Choix d’un type de formulaire

### Séance 1

- Liste des bonnes pratiques
- Composition de la structure

### Revue

- Présentation d’exemples
- Liste de ressources

### Séance 2

- Constituer sa liste d’outils
- Construire un templte

## Protocoles

Mettre à disposition des exemples de code fonctionnel permettant de tester des formulaires en ligne, ainsi que la liste des éléments à prendre en compte pou sa réalisation.

Accompagner le code d'une liste de ressources permettant de comprendre le fonctionnement du code et des ressources vers les librairies (ou exemples de code) utilisé sur le formulaire.

```HTML
<h1>Formulaire<h1>
<form>
  <fieldset>
    <legend>Se connecter - Générer un code sécurisé</legend>
    <p class="form-note">
      Texte de description du formulaire.
    </p>
    <p>
      <label for="login_email">Votre adresse e-mail</label>
      <input type="email" name="login_email" id="login_email" placeholder="ex. example@mail.com" value="" required="">
    </p>
    <p class="form-more">
      Indication supplémentaires.
    </p>
    <p class="form-submit">
      <input type="submit" class="button button--success" value="Valider">
    </p>
  </fieldset>
</form>
```

```HTML
<h2>Librairies</h2>
<ul>
  <li>Validation : <a href="https://hyperform.js.org">hyperform</a></li>
  <li>Persistence : <a href="https://gist.github.com/feimosi/f8704e33187b899860bd9b8061e591b2">persist-restore-form-data.js</a></li>
</ul>
```

```HTML
<h2>Ressources</h2>
<ul>
  <li>Validation : <a href="https://medium.com/the-ui-files/form-validation-with-javascript-4fcf4dd32846">Form validation with JavaScript</a></li>
  <li>Persistence : <a href="http://html5doctor.com/storing-data-the-simple-html5-way-and-a-few-tricks-you-might-not-have-known/">Storing Data the Simple HTML5 Way</a></li>
</ul>
```
