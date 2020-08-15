# Introduction to Google Firebase

# HTML
**Text input**
```
<input type="text" id="name" />
```

**Email input**
```
<input type="email" id="email" />
```

**File input**
```
<input type="file" id="file" />
```

**Button**
```
<button onclick="submitForm()">Submit</button>
```

# JavaScript
**JavaScript - getting input value using it's id**
```
document.getElementById("email").value
```

**JavaScript - getting file from file input using it's id**
```
document.getElementById("file").files[0]
```

**JavaScript - getting values of an object**
```
let records = Object.values(recordObject);
```

# Firebase
**Pushing data to realtime database**

```
firebase.database().ref("ref").push({
  name: "test",
  email: "test",
  comments: "test",
});
```

**Saving files to storage**
```
firebase.storage().ref(filename).put(file);
```

**Fetch data in realtime**
```
firebase.database().ref("ref").on('value', (data) => {
    let records =  data.val();
});
```


**Anonymous Auth**
```
firebase.auth().signInAnonymously().then(() => {
  // auth success
})
```

# More
**Slide**
https://docs.google.com/presentation/d/1cWWRGilpyXAHVE7otKy9_MOL-9jGUNIYWgmzSnqU3NM/edit?usp=sharing
