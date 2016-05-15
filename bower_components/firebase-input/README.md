`<firebase-input>` wraps a Firebase leaf in a paper-input for editing



    <template is="dom-repeat" items="{{leaves}}" as="leaf">
      <firebase-input firebase-root="https://YOUR-FIREBASE.firebaseio.com/YOUR-COLLECTION/YOUR-ITEM/LEAF-PATH" label="leaf"></firebase-input>
    </template>



In the above examplle replace YOUR-FIREBASE, YOUR-COLLECTION, YOUR-ITEM and LEAF-PATH with appropriate values from your Firebase.

Leaves are the full paths to Firebase values ie https://YOUR-FIREBASE.firebaseio.com/users/FIREBASE-KEY/name/first-name

The Firebase document is initiaized once the firebase-root is provided.
