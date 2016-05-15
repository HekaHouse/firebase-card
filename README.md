# firebase-card

`<firebase-card>` wraps the content into a paper-card container.

[API Docs and Demo](http://hekahouse.github.io/firebase-card/)

The card header contains the name property of the firebase-document.data,
each document value is available for editing in paper-input elements
via the show detail button.

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

[firebase-input](https://github.com/HekaHouse/firebase-input)

## Related

firebase-card is designed for use inside of [firebase-list](https://HekaHouse.github.io/firebase-list)
