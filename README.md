# A very basic Meteor + Vue boilerplate
This boilerplate serves as a Proof of concept of how easily Vue integrates with Meteor. 

> Please do not consider this as the best starting point for a mature app with Vue and Meteor 
for this its recommended to use the generic [Meteor Vue Boilerplate](https://github.com/chris-visser/meteor-vue-boilerplate).

## Getting Started
```bash
cd src && meteor npm install
```

This will install the babel/runtime, some Meteor stubs and the Vue dependency.

Run the below command to start the app
```bash
meteor
```

You can now write single file vue components with the .vue extension. App.js is 
the clientside entry of your app.

> This app will render as a client rendered app 'only'. Please follow the [Meteor + Vue integration guide](https://guide.meteor.com/vue.html) 
for a more mature setup with SSR and other benefits
