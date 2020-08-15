# firebase-intro



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

**Javascript - getting input value using it's id**
```
document.getElementById("email").value
```

**Javascript - getting file from file input using it's id**
```
document.getElementById("file").files[0]
```
