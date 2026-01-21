 let NomeDoHeroi = "Belith";
    let XPDoHeroi = [800, 5500, 4500, 12000, 3000];
    let NivelDoHeroi = "";

for(let i = 0; i< XPDoHeroi.length; i++ ) {

let XPAtual =  XPDoHeroi[i];
let NivelDoHeroi = "";


if(XPAtual <=  1000) { 
    NivelDoHeroi = "Ferro";
}
else if(XPAtual >= 1001 && XPAtual <= 2000) {
    NivelDoHeroi = "Bronze";
}
else if(XPAtual >= 2001 && XPAtual <= 5000) {
    NivelDoHeroi = "Prata";
}
else if(XPAtual >= 5001 && XPAtual <= 7000) {
    NivelDoHeroi = "Ouro";
}
else if(XPAtual >= 7001 && XPAtual <= 8000) {
    NivelDoHeroi = "Platina";
}
else if(XPAtual >= 8001 && XPAtual <= 9000) {
    NivelDoHeroi = "Ascendente";
}
else if(XPAtual >= 9001 && XPAtual <= 10000) {
    NivelDoHeroi = "Imortal";
}
else if(XPAtual >= 10001) {
    NivelDoHeroi = "Radiante";
}

console.log("O Heroi de nome " + NomeDoHeroi + " com "
    + XPAtual + " de XP esta no nivel: " + NivelDoHeroi);
}
