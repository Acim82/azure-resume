# azure-resume
My own azure resume, following ACG project video.


# First steps

- Frontend folder contains the website
- main.js contains visitor counter code

```js
const getVisitCount = () => {

    let count = 30;
    fetch(functionApi).then(response => {
        return response.json()
    }).then(response => {
        console.log("Website called function API.");
        count = response,count;
        document.getElementById("counter").innerText = count;        
    }).catch(function(error){
        console.log(error);
    });
    return count;

}
```

