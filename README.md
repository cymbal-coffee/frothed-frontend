Getting Started
---------------

 1. Create your project on the [Firebase Console](https://console.firebase.google.com).
 2. Enable the **Anonymous** sign-in provider in the **Authentication > SIGN-IN METHOD** tab.
 3. Enable Firebase Storage in the **Storage** part of the console and create a bucket
 4. Run `firebase deploy --project=YOUR_PROJECT_NAME` to deploy to your project

Bonus: can you modify the code you deployed, to see if you can get any additional points? Redeploy and reload the Firebase Hosting page to find out if you are successful!

**Hint:** if it fails to deploy, have you [enabled Cloud Storage in Firebase Console](https://firebase.google.com/docs/storage/web/start#create-default-bucket)?

**Second Hint:** If you deployed before creating the storage bucket, re-deploy once it's been created
