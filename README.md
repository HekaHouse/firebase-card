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
      firebase-root="https://YOUR-FIREBASE.firebaseio.com/YOUR-COLLECTION/"
      document-key="{{SOME-OBJECT.__firebaseKey__}}">
    </firebase-card>

In the above example replace YOUR-FIREBASE, YOUR-COLLECTION, SOME-OBJECT with appropriate values from your Firebase.

## Note

The Firebase document is initiaized once both the firebase-root and document-key are provided.

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

firebase-card depends on

[firebase-input](https://heka-house-polymer-demos.firebaseapp.com/firebase-input)

## Related

firebase-card is designed for use inside of [firebase-list](https://heka-house-polymer-demos.firebaseapp.com/firebase-list)
