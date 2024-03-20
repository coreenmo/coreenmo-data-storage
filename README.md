
## 💾 Requirements

* `Web Browser` - Can be used as an emulator to build applications. Example [Chrome, Firefox, Safari & Opera].
* `Internet` - Because many use CDN and to make it easier to find solutions to all problems.

## 🎯 How To Use

#### Example Syntax

```javascript
const DataStorage = require('./src/dataStorage');

// Create a new instance of DataStorage
const storage = new DataStorage();

// Set data
storage.setItem('key', 'value');

// Get data
const value = storage.getItem('key');
console.log(value); // Output: 'value'

// Remove data
storage.removeItem('key');
```

#### Explanation

* This package provides a simple interface to store and retrieve data using local storage.

#### Return Value

* `setItem(key, value)`: Sets the value for the given key.
* `getItem(key)`: Retrieves the value for the given key.
* `removeItem(key)`: Removes the value for the given key.

