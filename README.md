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

// Access using for in loop
for(let key in myCar)
console.log(`${key}:${myCar[key]}`);



//Accessing for of loop
for(let [key,value] of Object.entries(myCar) ){
    console.log(key +": "+value);
}

//Accessing using forEach
Object.entries(myCar).forEach(([key,value])=>{
    console.log(key+": "+value);
})

//Create your own resume data in JSON format

const myResume={
    name:"Vinod Kotagiri",
    age: 30,
    skills: ["HTML","CSS", "JS", "React", "MongoDB","Python"],
    mobile: "+919885718717",
    emial: "vinodkotagiri@icloud.com",

}
