# Day3_task

//For the given JSON iterate over all for loops (for, for in, for of, forEach)
const myCar={ </br>
   make: "Audi", </br>
   model: "A7", </br>
   year: 2019, </br>
   color: "Black", </br>
   Seats: 5, </br>
   price: "$75000", </br>
   fuel: "petrol", </br>
   milage: "12 Kmpl", </br>
}; </br>
</br>
// Access using for in loop</br>
for(let key in myCar)</br>
console.log(`${key}:${myCar[key]}`);</br>
</br>
</br>
</br>
//Accessing for of loop</br>
for(let [key,value] of Object.entries(myCar) ){</br>
    console.log(key +": "+value);</br>
}</br>
</br>
//Accessing using forEach</br>
Object.entries(myCar).forEach(([key,value])=>{</br>
    console.log(key+": "+value);</br>
})</br>
</br>
//Create your own resume data in JSON format</br>
</br>
const myResume={</br>
    name:"Vinod Kotagiri",</br>
    age: 30,</br>
    skills: ["HTML","CSS", "JS", "React", "MongoDB","Python"],</br>
    mobile: "+919885718717",</br>
    emial: "vinodkotagiri@icloud.com",</br>
};</br>
