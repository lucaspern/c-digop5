let palavra;


createCanvas(400, 400);

palavra=palavraAleatoria();
  
}

function palavraAleatoria();
  
let palavraAleatoria() ["caminhante, "caminho", "caminha"];

return radndom(palavras);
}

function inicializaCores() {
background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER, CENTER);
}
  
  function palavraParcial(minino, maximo) {
  let quantidade= map(mouseX, minimo, maximo, 1, palavra.length);
  let parcial=palavra.substring(0, quantidade); 
  return parcial;
  }
  
  function draw() {
  
  inicializaCores();
  
  let texto= palavraParcial(0,width);
    
  text(texto,200, 200);
    
  }
    
    function modonoturno(horario) {
    if (horario < 18) {
    console.long ("voce precisa ligar o modo escuro!");
   {else {
     console.long("modo noturno nao e necessario neste momento.");
      }     
   }    
     
  modoNoturno(15);   
  modoNoturno(20);
    
