![alt](/content/images/2015/02/input_recherche.png)

Ce composant est un _composant élémentaire_ de _Focus_. 

#Interface
## Cas d'usage
Ce composant peut être utilisé dans les cas suivants :

- Recherche rapide 
- Recherche contuextualisée 


## Maquettes
###### recherche par défaut
![alt](/content/images/2015/02/input_recherche3.png)

###### Recherche contextualisée
![alt](/content/images/2015/02/input_recherche.png)
![alt](/content/images/2015/02/input_recherche2.png)
![alt](/content/images/2015/02/input_recherche4-1.png)

## Interactions

### Erreurs

Le composant ne lève pas d'erreur: 

- La saisie est libre
- Le choix du contexte est libre.


### Aide

Si un contexte de recherche est définissable, une aide textuelle est affichée sous le composant pour guider l'utilisateur.

![alt](/content/images/2015/02/scope.png)

## Structure
- title
- block (son)
- help
- error
## Feedback

- Le contexte de recherche est sélectionné est affiché à gauche du champ de saisie.
- Lorsqu'une recherche est lancée par le composant, un spinner est affiché dans le champ de recherche, sur la droite.
- Lorsqu'aucun texte de recherche n'est défini, le composant affiche du texte qui indique à l'utilisateur ce qu'il peut saisir.

## Inspiration

[Linkedin](http://www.linkedin.com)
![alt](/content/images/2015/02/linkedin.png)

## Technical Configuration

The configuration is processed by the component reading the metadata from the data-binding and the attributes from the component.
The metadata are in the domain.

## Attributes

Attribute     | Options     | Possible               | Default       | Description
---           | ---         | ---                    | ---           | ---
`type`        | *string*    | `text`, `date`, `hour` | `text`        | Define the type of input for the rendering.

## Methods

If the component exposes methods in order to be able to interact with it.

Method         | Parameters   | Returns      | Description
---            | ---          | ---          | ---
`validate()`   | None.        | *boolean*    | Validate the input content depending on its metadata.
`getValue()`   | None.        | *object*     | get the input's depending on its metadata.

## Events

Which events are triggered by the user.

Event         | Description
---           | ---
`change`      | The input calue changed.

## Example
```html
<input type='date'/>
```


## Test

## Demo
![Input](http://images.ientrymail.com/webpronews/article_pics/html-speech-input.jpg)

