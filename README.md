# firebase-card

`<firebase-card>` wraps the content of a firebase-document into a paper-card container.

[API Docs and Demo](https://heka-house-polymer-demos.firebaseapp.com/firebase-card)

[Source](http://github.com/hekahouse/firebase-card/)

The card header contains the name property of the firebase-document.data,
each document value is available for editing in paper-input elements
via the show detail button.

## Install

    bower install --save HekaHouse/firebase-card

## Example

    <firebase-card
      app-name="heka-house"
      user="{{user}}"
      app="{{app}}"
      firebase-branch="/sample"
      document-key="Hatfield Sparks" readonly>
    </firebase-card>

The Firebase document is initiaized once the user and app properties are provided.

These come from associated firebase-app and firebase-auth elements

## Note

firebase-branch corresponds to the path property of a firebase-document,

this path should lead to a collection, designed to be a collection from a [firebase-list](https://heka-house-polymer-demos.firebaseapp.com/firebase-list)

document-key represents the key for an item in the collection specified in firebase-branch

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

firebase-card depends on

[firebase-input](https://heka-house-polymer-demos.firebaseapp.com/firebase-input)

and uses the pre-release [polymerfire](https://github.com/firebase/polymerfire)

## Related

firebase-card is designed for use inside of [firebase-list](https://heka-house-polymer-demos.firebaseapp.com/firebase-list)
