# Trained-Models 
List of trained tensorflow javascript models for web applications.

## Usage
```js
tf.loadLayersModel("https://models.lovesaroha.com/model-name/model.json").then(savedModel => {
    model = savedModel;
}).catch(e => { console.log(e); });
```
