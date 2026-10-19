# 🎯 Jogo do Número Secreto

Jogo de adivinhação feito com **HTML, CSS e JavaScript puro**: o computador sorteia um número de 1 a 10 e você tenta descobrir qual é, com dicas a cada chute.

🎮 **Jogue agora:** https://jogonumerosecreto-nine-lovat.vercel.app/


---

## Como funciona

1. O jogo sorteia um número secreto entre **1 e 10**.
2. Você digita um palpite e clica em **Chutar**.
3. O jogo informa se o número secreto é **maior** ou **menor** que o seu chute.
4. Quando você acerta, ele mostra **em quantas tentativas** você conseguiu.
5. Clique em **Novo jogo** para jogar de novo.

## Funcionalidades

- 🔢 **Sorteio sem repetição:** os números já sorteados ficam guardados em uma lista e só voltam a aparecer depois que todos de 1 a 10 forem usados.
- 💡 **Dicas a cada chute** (maior ou menor).
- 🧮 **Contador de tentativas**, com plural e singular corretos ("1 tentativa" ou "3 tentativas").
- 🔊 **Narração por voz:** todos os textos da tela são falados em português usando a API ResponsiveVoice.
- 🔁 **Botão "Novo jogo"**, que só fica ativo depois do acerto.
- 🌐 **Publicado na Vercel**, jogável direto no navegador.

## Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura da página |
| CSS3 | Layout e estilo |
| JavaScript | Lógica do jogo e manipulação da tela (DOM) |
| [ResponsiveVoice](https://responsivevoice.org/) | Leitura dos textos em voz alta |
| Vercel | Hospedagem |

## O que aprendi

- Criar e reutilizar **funções** (ex.: `exibirTextoNaTela`, `gerarNumeroAleatorio`).
- Usar **condicionais** para comparar o chute com o número secreto.
- Trabalhar com **listas (arrays)** e **recursão** para evitar números repetidos.
- **Manipular o DOM**: ler o valor do campo, alterar textos e habilitar ou desabilitar botões.
- Versionar o projeto com **Git e GitHub** e publicar na **Vercel**.

## Como rodar localmente

```bash
git clone https://github.com/Leonardo-CB17/jogoDoNumero.git
cd jogoDoNumero/3386-git-github-projeto_inicial
```

Depois é só abrir o arquivo `index.html` no navegador.

## Créditos

Projeto desenvolvido durante o curso de JavaScript da [Alura](https://www.alura.com.br/).

---

👤 **Leonardo Cabral Basilio**, estudante de Engenharia da Computação na FIAP
[LinkedIn](https://www.linkedin.com/in/leonardo-cabral-basilio-24697b3b9) · [GitHub](https://github.com/Leonardo-CB17)
