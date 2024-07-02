#   Pedido-de-namoro 
* DOTIPE html.
** html lang="pt-br">lang="pt-br">
<cabeça>
** meta-charset="UTF-8">charset="UTF-8">
<* meta name= "viewport" content="width=largura do dispositivo, escala inicial=1.0">name="viewport" content="width=device-width, escala inicial=1.0">
(título: Pedido de Namoro)</título>
Estilo:
   corpo {   
 Display: flex; 
            justify-content: center; justify-content: center;   
 itens de linha: centro; 
 Altura: 100vh; 
 cor de fundo: #f0f0f0; 
           font-family: Arial, sans-serif;   
     } 
 .contentor { 
           text-align: center;   
       }   
       #sim  { {    
   enchimento: 20px 40px;   
   Tamanho da fonte: 24px;   
   cor de fundo: #4CAF50;   
   cor: branco;   
   fronteira: nenhuma;   
   cursor: ponteiro;   
   delineamento: nenhum;   
   transição: cor de fundo 0.3s;   
       }   
 #sim: hover { hover { 
   cor de fundo: #45a049;   
       }   
 #nao { 
   enchimento: 20px 40px;   
   Tamanho da fonte: 24px;   
   cor de fundo: #f44336;   
   cor: branco;   
   fronteira: nenhuma;   
   cursor: ponteiro;   
   delineamento: nenhum;   
   transição: transformar 0.3s ease-in-out;   
   posição: absoluta;   
 top: 50%; 
   esquerda: 50%;   
   Transformar: traduzir(-50%, -50%)   
       }   
 #nao:hover { 
 animação: shake 0.5s ease-in-out infinito; 
       }   
 @keyframes shake { 
           0%, 100% {   
   Transformar: traduzir(-50%, -50%) rotar (0deg)   
           }   
           10%, 30%, 50%, 70%, 90% {   
   Transformar: traduzir(-50%, -50%) rotar(-10deg)   
           }   
           20%, 40%, 60%, 80% {   
   Transformar: traduzir(-50%, -50%) rotar 10 deg;   
           }   
       }   
</* estilo >>
</</cabeça>
<corpo:>
<classe De Div="contentor">classe="contentor">
     <h1>Você aceita namorar comigo?</h1> <h1>Você aceita namorar comigo?</h1>
         <  botão    id="sim" onclick="Alerta('Parabéns! 🎉')">Sim</botão> <  botão    id="sim" onclick="Alerta('Parabéns! 🎉')">Sim</botão>  </botão>   
       <botão  id="Não" onclick="moveNao()">Não</botão>   
</</Div>

(script)...
função moveNao() {{
 var naoButton = document.getElementById('nao') 
 var newX = Math.random() * (window.innerWidth - naoButton.clientWidth) 
 var newY = Math.random() * (window.innerHeight - naoButton.clientHeight) 
    
 naoButton.style.esquerda = newX + 'px'; naoButton.style.left = newX + 'px';
 naoButton.style.top = newY + 'px'; 
}
</</script>

<//corpo:>
</</html.
