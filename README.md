# Trained-Models 
List of trained tensorflow javascript models for web applications.

## Usage
```js
let model;
// Serve model files using localhost server.
tf.loadLayersModel("http://localhost/model-name/model.json").then(savedModel => {
    model = savedModel;
}).catch(e => { console.log(e); });
```
