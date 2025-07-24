Segue o codigo dentro do Arquivo index.js


let nomeDoHeroi = "Euclides";
let XpDoHeroi = 10000;
let nivel = "";

if (XpDoHeroi <= 1000) {
    nivel = "Ferro";
} else if (XpDoHeroi <= 2000) {
    nivel = "Bronze";
} else if (XpDoHeroi <= 3000) {
    nivel = "Prata";
} else if (XpDoHeroi <= 4000) {
    nivel = "Ouro";
} else if (XpDoHeroi <= 5000) {
    nivel = "Platina";
} else if (XpDoHeroi <= 7000) {
    nivel = "Diamante";
} else if (XpDoHeroi <= 8000) {
    nivel = "Ascendente";
} else if (XpDoHeroi <= 9000) {
    nivel = "Imortal";
} else {
    nivel = "Radiante";
}

console.log(`O Herói de nome ${nomeDoHeroi} está no nível de ${nivel}`);
