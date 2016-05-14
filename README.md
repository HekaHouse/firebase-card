`<firebase-card>` wraps the content into a flexwrap paper-card container
and generates a firebase-input for each document leaf




    <firebase-card
      firebase-root="https://YOUR-FIREBASE.firebaseio.com/YOUR-COLLECTION"
      document-key="{{SOME-OBJECT.__firebaseKey__}}">
    </firebase-card>




In the above examplle replace YOUR-FIREBASE, YOUR-COLLECTION with appropriate values from your Firebase.

SOME-OBJECT is any Firebase document coming from YOUR-COLLECTION.

The Firebase document is initiaized once both the firebase-root and document-key are provided.
