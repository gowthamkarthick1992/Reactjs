

 const name='I am trying to develope React function'

function print () 
{
const name='it is called from function scope'
console.log(name)

if (true)
{
const name='it is called from block scope'
console.log(name)
}
}

console.log(name)
print() 
