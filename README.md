# MyPortfolio
 Portfolio Website
![Screenshot (14)](https://user-images.githubusercontent.com/100525567/196047446-ccd60263-94f8-4021-8c37-e01aaeec5979.png)
let capitalArray = ["a","b","c","d","e","f","g","h","i","j","k","l","m","n","o","p","q","r","s","t","u","v","w","x","y","z"];
let smallArray = ["A","B","C","D","E","F","G","H","I","J","K","L","M","N","O","P","Q","R","S","T","U","V","W","X","Y","Z"];

let comparearray = [capitalArray, smallArray];
let allalphabets = document.getElementById("allalphabets");
setInterval(() => {
    let getCapitalAlphabet = Math.floor(Math.random() * 26);
    let getSmallAlphabet = Math.floor(Math.random() * 2);
    let get = comparearray[getSmallAlphabet];
    let finalget = get[getCapitalAlphabet];

has
    // console.log(finalget);
    allalphabets.innerHTML += finalget;
}, 2000);
