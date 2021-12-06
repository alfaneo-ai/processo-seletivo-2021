# Processo Seletivo 2021

Bem-vindo ao exame técnico para o processo seletivo da Juridics.
Em primeiro lugar, agradecemos pelo seu interesse e sua disponibilidade em realizar mais esta etapa do processo seletivo.
Consideramos fundamental esta etapa do processo, pois permitirá que tanto você quanto a Juridics se conhecam um pouco melhor.

Desde já, salientamos que este exame irá medir o seu nível de "se virômetro", ou seja, o quanto é capaz de encontrar
solucoes no dia a dia. Portanto, você está livre para pesquisar na internet e até mesmo copiar código dos outros.
Porém, apresente um código final legível, entendível e organizado, pois isso será usado como critério de avaliacao.

Para realizar este exame, primeiramente crie um FORK deste repositório na sua conta e faca commit de todas as respostas neste FORK.
Este exame é composto de 5 questões, a seguir:

### Questão 1) Desenvolva uma funcao *em javascript* para verificar se é número primo
Um número é classificado como primo se ele é maior do que um e divisível apenas por um e por ele mesmo.
A funcao deve receber como entrada um número inteiro e devolver como saída um true quando o número for primo e false quando não for. 
A funcao não deve permitir receber números acima de 100, quando isso acontecer devolva uma excecão.

### Questão 2) Desenvolva *em java* as classes que representam um modelo conceitual
Transcreva para classes java o modelo conceitual abaixo, observe os padrões de nomenclaturas e os tipos convencionados em Java.
Dentro dos métodos das classes não deve conter nenhuma implementacao.
Tome cuidado com a cardinalidade e navegabilidade dos relacionamentos entre classes, pois isso gera consequências no código.
![Modelo Conceitual](questao2/modelo.jpeg)

### Questão 3) Desenvolva *em python* endpoints REST para cadastro de investidor
Crie 3 endpoints que serão usados para inserir, alterar e remover investidor.
Atencao aos pontos abaixo: 
 - É permitido utilizar frameworks python, tais como: Flask, Django e outros;
 - Não deve ser utilizado banco de dados (relacional ou NoSQL), mas os dados devem ser mantidos na memória ou em disco através de arquivo texto;
 - O cadastro de investidor deve conter os seguintes campos: nome, CPF, email, data de nascimento e valor que deseja investir.

Atencão: crie o arquivo requirements.txt para registrar as libs.

### Questão 4) Desenvolva uma funcao *em python* para calcular se duas frases são similares
A funcão deve receber duas frases no *idioma Inglês* como entrada. Deve ser utilizado frases curtas de até 300 caracteres cada,
e devolver o nível de similaridade entre as frases. Este nível (score) normalmente é um número entre 0 e 1, onde quanto mais perto de
1 mais similar e quanto mais perto de 0 menos similar.
Nesta questão, gostaríamos de avaliar sua capacidade de realizar pesquisa. 
Existem algumas libs que fazem isso em python, descubra quais são e aprenda a utiliza-las.

Atencão: crie o arquivo requirements.txt para registrar as libs.

### Questão 5) Desenvolva *html e css* a tela de exemplo
Cria uma tela utilizando somente HTML e CSS o mais parecido possível com o desenho a seguir.
![Tela a ser desenhada](questao5/exemplo.png)
