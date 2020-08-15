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
