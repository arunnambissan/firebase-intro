# Firebase
**Saving to database**

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

# JavaScript
**JavaScript - getting input value using it's id**
```
document.getElementById("email").value
```

**JavaScript - getting file from file input using it's id**
```
document.getElementById("file").files[0]
```

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
