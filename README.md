# f-input

This component is the defaut Focus input component and is _elementary_

## Use case

###  context

This component is used in order to build

### [ui](https://pierr.github.io/f-input/)

- rendu par défaut
- Erreurs
- Aide
- Feedback


## Configuration

Domain, metadata

## Attributes

Attribute     | Options     | Possible               | Default       | Description
---           | ---         | ---                    | ---           | ---
`type`        | *string*    | `text`, `date`, `hour` | `text`        | Define the type of input for the rendering.

## Methods

Method         | Parameters   | Returns      | Description
---            | ---          | ---          | ---
`validate()`   | None.        | *boolean*    | Validate the input content depending on its metadata.

## Events

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


