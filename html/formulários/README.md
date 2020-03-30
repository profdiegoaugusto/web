# Pokémon

Há mais de 10 anos, crianças do mundo inteiro vêm descobrindo o mundo encantado dos Pokémon. Hoje, a família de produtos Pokémon inclui videogames, o jogo Pokémon Estampas Ilustradas, a série de TV animada, filmes, brinquedos e muito mais. Muitos pais acreditam que o Pokémon Estampas Ilustradas e os videogames do Pokémon estimulam seus filhos a aprender a ler, já que a leitura é indispensável na maioria dos jogos do Pokémon. Os jogos também estimulam o pensamento estratégico e, em muitos casos, habilidades matemáticas básicas. O Pokémon valoriza muito o espírito esportivo e o respeito pelos outros jogadores.

## O que são Pokémon?

Pokémon são criaturas de todas as formas e tamanhos que convivem com os humanos na natureza. Na grande maioria, os Pokémon não falam, exceto para proferir seus nomes. Os Pokémon são criados e comandados por seus donos (os chamados "Treinadores"). No decorrer das aventuras, os Pokémon crescem e ganham experiência, podendo até mesmo evoluir para Pokémon mais fortes. Alguns Pokémon, como Pikachu, Piplup e Charizard, possuem papéis de destaque na série de videogames, no jogo Estampas Ilustradas e nos programas de TV, mas eles são apenas algumas das quase 500 criaturas que habitam o universo dos Pokémon.

**Fonte:** [Webiste Oficial - Pokémon](https://www.pokemon.com/br/guia-para-pais/)

## Ponto de Partida

Para começar esse exercício e fazer a marcação em HTML, você deverá criar o arquivo `cadastro_pokemon.html` ; usando o seu editor de código-fonte favorito que você irá utilizar para fazer este trabalho, por exemplo:

* [Visual Studio Code](https://code.visualstudio.com/)
* [Atom](https://atom.io/)
* [Sublime](sublimetext.com)

## Resumo do Projeto

Para este projeto, sua tarefa é marcar usando a sintaxe do HTML5, um formulário de cadastro de Pokémons para os dados da tabela abaixo. Você deverá estruturar o documento geral com uma estrutura apropriada conforme a sintaxe e semântica do HTML5, incluindo os elementos: `<!DOCTYPE html>`, `<html>`, `<head>` e `<body>`; além disso, adicione corretamente quando necessário:

* **Elementos de Formulários:** `<form>, <fieldset>, <legend>, <label>;`
* **Controles de Formulário:**
    * Campos de Texto de Linha Única;
    * Itens Verificáveis: caixas de seleção e botões de opção
    * Campos Numéricos;
    * Botões;
    * Controles Suspensos.



| Coluna          | Descrição                                                                                                                                                                                                                        |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| numero          | Chave Primária: o número do Pokémon no Pokedex Nacional                                                                                                                                                                          |
| nome            | Nome do Pokémon                                                                                                                                                                                                                  |
| tipo1           | Todas as criaturas Pokémon e seus movimentos recebem determinados tipos. Cada tipo tem vários pontos fortes e fracos no ataque e na defesa, ou seja, cada Pokémon tem um tipo que determina sua fraqueza/resistência aos ataques |
| tipo2           | O tipo secundário do Pokémon caso ele possua                                                                                                                                                                                     |
| total           | Soma de todas as estatísticas básicas (Pontos de Vida, Ataque, Defesa, Ataque Especial, Defesa Especial e Velocidade)                                                                                                            |
| hp              | HP (Hit Points ou Health Points), define quanto dano um Pokémon pode suportar antes de desmaiar                                                                                                                                  |
| ataque          | O ataque base do Pokémon                                                                                                                                                                                                         |
| defesa          | A defesa base do Pokémon                                                                                                                                                                                                         |
| ataque_especial | O ataque especial base do Pokémon                                                                                                                                                                                                |
| defesa_especial | A defesa especial base do Pokémon                                                                                                                                                                                                |
| velocidade      | A velocidade base do Pokémon                                                                                                                                                                                                     |
| geracao         | Número da geração em que o Pokémon foi introduzido                                                                                                                                                                               |
| lendario        | Valor Booleano que indica se o Pokémon é lendário ou não                                                                                                                                                                         |
| cor             | A cor do Pokémon                                                                                                                                                                                                                 |
| altura_m        | Altura em metros do Pokémon                                                                                                                                                                                                      |
| peso_kg         | Peso em Kilos do Pokémon                                                                                                                                                                                                         |
| taxa_captura | A taxa de captura do Pokémon é um número entre 0 e 255, quanto maior, melhor |

### Observações

* **Tipos**: Aço, Água, Dragão, Elétrico, Fada,  Fantasma, Fogo, Gelo, Inseto,  Lutador, Normal, Pedra, Planta, Psíquico, Sombrio, Terra, Venenoso, Voador;
    * Mínimo 1 e Máximo 2 dentre os valores acima;
* **Cor**: Amarelo, Azul, Branco, Cinza, Marrom, Preto, Rosa, Roxo, Verde, Vermelho;
* **Lendário**: Sim ou Não;
* **Geração**: 1 até 7 inclusive;
* **Colunas Numéricas:** número, total, hp, ataque, defesa, ataque_especial, defesa_especial, velocidade, altura_m, peso_kg, taxa_captura;
    * **HP**: 1 até 255 inclusive;
    * **Taxa de Captura**: 0 até 255 inclusive;




## Dicas & Sugestões

* Use o [validador HTML](https://validator.w3.org/) do W3C para validar seu HTML;
* Consulte a lista de [elementos HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element) para obter informações detalhadas de sobre cada tag.



## REFERÊNCIAS

* [Guia de formulários HTML](https://developer.mozilla.org/pt-BR/docs/Web/Guide/HTML/Forms)
* [Como estruturar um formulário HTML](https://developer.mozilla.org/pt-BR/docs/Web/Guide/HTML/Forms/How_to_structure_an_HTML_form)
* [Basic native form controls](https://developer.mozilla.org/en-US/docs/Learn/Forms/Basic_native_form_controls)
* [The HTML5 input types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)
* [Other form controls](https://developer.mozilla.org/en-US/docs/Learn/Forms/Other_form_controls)

