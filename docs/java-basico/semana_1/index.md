# Semana 1 (de 08 a 17/abril)

Na semana passada preparamos nosso ambiente de trabalho e fizemos um HelloWorld <3. 
Agora vamos aprender o basicão do Java, estudando como funcionam as variáveis! 


**Cronograma da semana:**

| Conteúdo | Link |
| --- | --- |
| Introdução à variáveis | [Aula 10 curso Loiane](https://www.youtube.com/watch?v=ELBqT_rueAQ&list=PLGxZ4Rq3BOBq0KXHsp5J3PxyFaBIXVs3r&index=13) |
| Tipos primitivos | [Aula 11 curso Loiane](https://www.youtube.com/watch?v=aqiB58NpKLw&list=PLGxZ4Rq3BOBq0KXHsp5J3PxyFaBIXVs3r&index=14) |
| Operadores | [Aula 13 curso Loiane](https://www.youtube.com/watch?v=199tKAE6sxo&list=PLGxZ4Rq3BOBq0KXHsp5J3PxyFaBIXVs3r&index=16) |
| Exercícios | Ver seção exercícios abaixo |


Conteúdo alternativo: 
Se você quiser reforçar o aprendizado ou prefere ter o conteúdo em formato texto, você pode ver esse conteúdo na Apostila da Caelum.
A diferença (além do formato texto x vídeo), é que na apostila da Caelum o conteúdo tá bem resumido e direto, enquanto que nas aulas da Loiane, ela explica tudo com exemplos, detalhes, etc.

| Conteúdo | Link |
| --- | --- |
| Declarando e usando variáveis | [Seção 3.1 Apostila Caelum](https://www.caelum.com.br/apostila-java-orientacao-objetos/variaveis-primitivas-e-controle-de-fluxo/#declarando-e-usando-variveis) |
| Tipos primitivos e valores | [Seção 3.2 Apostila Caelum](https://www.caelum.com.br/apostila-java-orientacao-objetos/variaveis-primitivas-e-controle-de-fluxo/#tipos-primitivos-e-valores) |
| Exercícios | Ver seção exercícios abaixo |


**Exercícios:**
Programação é treino! Nós não iremos aprender a programar só vendo as aulas, então vamos colocar a mão na massa para reforçar o que aprendemos.

1. Antes de tudo, crie um projeto na sua IDE para colocar os arquivos Java que iremos criar nos exercícios. Pode colocar o nome que quiser no projeto (`java-basico`, por exemplo).
É a primeira vez que tá criando um projeto e não sabe como fazer? Aqui abaixo tem a explicação de como fazer em cada IDE:

  * Eclipse: Vai no menu `New` e depois em `Java Project`.  A Loiane [explica aqui](https://youtu.be/74QEhBpzixs?list=PLGxZ4Rq3BOBq0KXHsp5J3PxyFaBIXVs3r&t=1352) com fazer.
  * NetBeans: Vai no menu `File` e depois em `Project` e em `Project Java Application`.  A Loiane [explica aqui](https://youtu.be/74QEhBpzixs?list=PLGxZ4Rq3BOBq0KXHsp5J3PxyFaBIXVs3r&t=1842) com fazer.
  * IntelliJ: `Create new Project` ou `File` -> `New` -> `Project`  

**Exercício 1: Meus dados**

Crie uma classe chamada MeusDados com um bloco main. O método main terá variáveis que irão guardar informações suas: 
* `nome` 
* `idade`
* `altura` (em metros, por exemplo 1.58)
* `gostoDeJava` (sim ou não?) - nessa tem que responder que sim hein hahahah

Para cada variável determine qual o tipo é o mais adequado. Por exemplo, para guardar seu nome, o tipo adequado é String, portanto você vai declarar/inicializar a variável assim:
`String nome = "Seu nome vai aqui";`

No bloco main, declare e inicializa as variáveis contendo seus dados e em seguida imprima-as no console. Um exemplo de saída:

```
Meu nome é: Taiza
Minha idade é: 34
Minha altura é: 1.60
Eu gosto de Java: true
```

**Exercício 2: Quanto vale o valor da hora de trabalho de Maria?**

Maria está querendo saber quanto vale o valor da hora de trabalho dela e pediu sua ajuda nisso.   
Faça um programa que calcula o valor da hora de trabalho de Maria. Ela recebe um salário mensal de R$2.500,50 e trabalha 40h/semana. 
 
Crie uma classe chamada CalculoDaHora com um bloco main. No método main declare três variáveis (identifique qual o tipo mais adequado): 
* `salario` (valor total do salário = R$2.500,50) 
* `horasSemana` (qtas horas ela trabalha por semana = 40 horas)
* `horasMes` (qtas horas ela trabalha por mês. Utilize a variável anterior `horasSemana` para calcular a qtd de horas de 1 mês (1 mês = 4 semanas))

Em seguida, crie outra variável chamada `valorDaHora` que possui o valor da hora de trabalho de Maria. Dica: use as variáveis `salario` e `horasMes` para calcular a hora de trabalho de Maria. Imprima o valor da hora de Maria. Seu programa deve imprimir algo assim:

```
O valor da hora de trabalho de Maria é: XXXXX (XXXXX vai ser o valor que seu programa vai calcular)
```

**Exercícios extras**

A Loiane fez uma lista de exercícios extras bem legais, link: [https://www.slideshare.net/loianeg/curso-java-bsico-exerccios-aulas-11-12-13](https://www.slideshare.net/loianeg/curso-java-bsico-exerccios-aulas-11-12-13).

Além disso, [aula 13](https://www.youtube.com/watch?v=199tKAE6sxo&list=PLGxZ4Rq3BOBq0KXHsp5J3PxyFaBIXVs3r&index=16), ela resolve os problemas. É otimo para entender a resolução e tirar as dúvidas, mas lembre-se: **programação é treino**, então antes de ver a Loiane resolvendo o exercício, tente fazer antes! Só depois disso que veja a resolução.


## Dúvidas?
Está com dúvidas? Quer compartilhar alguma coisa? Fala lá no canal #grupo_estudos_online do Slack =)


