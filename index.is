let user = {
    hobby:'',
    premium:true,

}
user.hobby = 'skydiving'
user.premium = false
user.mood = 'happy'
for (let key in user){
    console.log(key,":",user[key])
}
function countProps(obj) {
    return Object.keys(obj).length;
}

const user2 = { name: "Ivan", age: 25, city: "Kyiv" };
console.log(countProps(user2));
function findBestEmployee(employees) {
    let bestName = Object.keys(employees)[ Object.values(employees).indexOf(Math.max(...Object.values(employees)))]

    return bestName;
}

const team = {
    Anna: 29,
    Ivan: 35,
    Petro: 18
};

console.log(findBestEmployee(team)); // Ivan
function countTotalSalary(employees) {
    let total = 0;

    for (const salary of Object.values(employees)) {
        total += salary;
    }

    return total;
}
const salaries = {
    Anna: 1000,
    Ivan: 1500,
    Petro: 1200
};

console.log(countTotalSalary(salaries));
function getAllPropValues(arr, prop) {
    const result = [];
    for (const obj of arr) {
        result.push(obj[prop])
    }
    return result;
}



const products = [
    { name: "apple", price: 30 },
    { name: "banana", price: 20 },
    { name: "orange", price: 25 }
];

console.log(getAllPropValues(products, "name"));
function calculateTotalPrice(allProducts, productName) {
    let arr = allProducts.filter(el => el.name === productName)
    if (arr){return arr[0].price * arr[0].quantity}
}


const shop = [
    { name: "apple", price: 30, quantity: 2 },
    { name: "banana", price: 20, quantity: 5 },
    { name: "apple", price: 30, quantity: 3 }
];

console.log(calculateTotalPrice(shop, "apple"));
