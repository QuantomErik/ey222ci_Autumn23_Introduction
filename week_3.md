### Code
```javascript

let firstName = 'Neo'
const lastName = 'Yang'
const city = 'Stockholm'
let age = 18
const occupation = 'student'

if (typeof age === 'number') {
    age = 1337
}

if (typeof firstName === 'string') {
    firstName = 'Erik'
}

console.log('Hello my name is '+ firstName +', I am '+age+' years old.')

if (occupation === 'student')
if (city === 'göteborg') {
    console.log(`I am a student at Lnu ${occupation} and living in ${göteborg}.`)
}  else {
    console.log(`I am a student at Lnu ${occupation} and living in ${city}.`)
}
```