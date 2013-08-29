## Asynchronizer JavaScript (and jQuery) File

---

This works hand-in-hand with the Asynchronizer's back-end API. The API is available in [PHP](https://github.com/Asynchronizer/PHP).

---

### Requirements

- [jQuery](http://jquery.com/)
- [PHP](https://github.com/RaideIO/PHP/tree/master/Traffic) Back-end

---

### Function List

```javascript
setSubmitURL(url)
```

---

### setSubmitURL() - Sets the URL that we will submit the Traffic data to.

Parameter(s)

```
string	url
```

Example(s)

```javascript
// Sets the URL that we will submit the Traffic data to, which will use the API.
Asynchronizer.setSubmitURL("back-end/submit.php");
```
