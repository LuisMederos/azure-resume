# azure-resume
My own azure resume - following ACG project video (https://www.youtube.com/watch?v=ieYrBWmkfno)

# First Steps

- Frontend Folder contains the website. 
- main. js contains visitor counter code. 

```js 

  let count = 30; 
    fetch(functionApi).then(response => {
        return response.json
    }).then(respone => {
        console.log("Website called function API.");
        count = response.count; 
        document.getElementById("counter").innerText = count; 
    }).catch(function(error){
        console.log(error);
    });
{
    return count;
}
```