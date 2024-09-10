## API debugging 
`https://insomnia.rest/`

## link to course
`https://btholt.github.io/complete-intro-to-web-dev-v3/lessons/welcome-to-the-class/get-set-up`

## Making an API POST Request
```js
assync function addNewDoggo(){
   const promise = await fetch(DOG_URL, {
     method: "POST",
     body: JSON.stringify({"word": "intent"})
});

```
## popmotion 
`https://popmotion.io/`

# This help build the project 
```js

npm install --global pracel

parcel index.html

npm install popmotion@11

parcel index.html
```
