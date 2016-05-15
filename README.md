`<firebase-card>` wraps the content into a paper-card container.
The card header contains the name property of the firebase-document.data,
each document property is available for editing via the show detail button.



      <firebase-card
        firebase-root="https://YOUR-FIREBASE.firebaseio.com/YOUR-COLLECTION/"
        document-key="{{SOME-OBJECT.__firebaseKey__}}">
      </firebase-card>



In the above examplle replace YOUR-FIREBASE, YOUR-COLLECTION, SOME-OBJECT with appropriate values from your Firebase.

The Firebase document is initiaized once both the firebase-root and document-key are provided.
