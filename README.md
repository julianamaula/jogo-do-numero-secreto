<h1 align="center">Jogo do número secreto
</h1>


<p align="center">

![image](https://github.com/user-attachments/assets/5ea76cc6-0277-40d3-b68c-f6f12d82c8d1)


</p>

Este projeto faz parte do curso de lógica de programação: “Explore funções e listas” proposto pela Alura, uma plataforma online de cursos de tecnologia, na turma G8 - ONE. É um projeto simples que nos permite explorar a criação de variáveis, funções, listas e toda a estrutura que compõe este jogo. As tecnologias utilizadas são HTML, CSS e JavaScript, incluindo a Web Speech API para reconhecimento e síntese de voz.



# ![3206042](https://github.com/user-attachments/assets/15662eaa-f2f4-46fa-8caa-a53fd84fe42c) Tecnologias Utilizadas

![](https://img.shields.io/badge/HTML-ff6905 ) ![](https://img.shields.io/badge/CSS-142cff )
![](https://img.shields.io/badge/JavaScript-ffff00 ) ![](https://img.shields.io/badge/Web%20Speench%20API-00a821 )

# ![4706330](https://github.com/user-attachments/assets/20c13f16-d6c9-4c7c-8b82-87c93e3c13cd) Acesso ao projeto

Você pode [acessar o código fonte inicial](https://github.com/julianamaula/jogo-do-numero-secreto)


# ![831842](https://github.com/user-attachments/assets/1e2f326f-696d-4e43-ab94-51de22691ca7) Como Usar

1. Clone o repositório para o seu ambiente local:
   ```bash
   git clone https://github.com/seu-usuario/jogo-do-numero-secreto.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd jogo-do-numero-secreto
   ```

3. Abra o arquivo `index.html` no seu navegador.

# ![1448776](https://github.com/user-attachments/assets/00570b30-04d8-4c3f-875d-421fe811001a) Estrutura do Projeto

- `index.html`: Arquivo principal HTML que contém a estrutura da página.
- `style.css`: Arquivo CSS para estilização da página.
- `app.js`: Arquivo JavaScript que contém a lógica do aplicativo.

# ![5486197 (1)](https://github.com/user-attachments/assets/25223a38-3e19-4230-8109-60abadfdaac9) Funções Principais

Esta função gera um número aleatório entre 1 e numeroLimite (10, neste caso) e garante que esse número não tenha sido sorteado anteriormente, evitando repetições. Se todos os números já foram sorteados, ela limpa a lista de números sorteados.
- ` gerarNumeroAleatorio()`
##

Esta função exibe o texto na tela em um elemento específico (definido por tag). Ela também utiliza a Web Speech API para falar o texto em voz alta, se suportado pelo navegador.
- `exibirTextoNaTela()`
##

Esta função exibe a mensagem inicial do jogo, incluindo o título "Jogo do número secreto" e a instrução "Escolha um número entre 1 e 10". Ela utiliza a função exibirTextoNaTela para isso.
- `exibirMensagemInicial()`
##

Esta função verifica se o chute do usuário (número inserido) é igual ao número secreto. Se for igual, ela exibe uma mensagem de acerto e habilita o botão de reiniciar. Caso contrário, ela informa se o número secreto é maior ou menor e incrementa o número de tentativas.
- `verificarChute()`
##

Esta função limpa o campo de input onde o usuário insere seu chute.
- `limparCampo()`
##

Esta função reinicia o jogo, gerando um novo número secreto, limpando o campo de input e exibindo a mensagem inicial novamente.
- `reiniciarJogo()`
##


# ![5827678](https://github.com/user-attachments/assets/d29b782f-fbfd-4afa-9cef-9fb13d1eb234) Licença

Este projeto está licenciado sob a [MIT License](LICENSE).


![GitHub Org's stars](https://img.shields.io/github/stars/juliana?style=social)

![](https://img.shields.io/badge/LICENÇA-MIT-blue) ![](https://img.shields.io/badge/npm-v4.1.0-00a821) 
