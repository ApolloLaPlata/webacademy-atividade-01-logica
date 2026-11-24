# Atividade 1 — Introdução à Lógica de Programação e Algoritmos

**Curso:** Web Academy UFAC  
**Disciplina:** Algoritmos e Lógica de Programação  
**Aluno:** Vinicius Miranda de Farias

## Questão 1 — Conceitual (2,5 pontos)

### 1. Definição de algoritmo (Forbellone e Eberspächer)

Algoritmo é uma sequência finita e ordenada de passos, bem definidos, que executados um após o outro levam à solução de um problema ou à execução de uma tarefa. Não é somente código: é um procedimento geral, descrito de forma clara e precisa, que recebe uma entrada e produz uma saída em tempo finito.

### 2. Propriedades fundamentais segundo Knuth

| Propriedade | Significado |
| --- | --- |
| Finitude | O algoritmo termina após um número finito de passos. |
| Definição exata | Cada passo é inequívoco, sem ambiguidade. |
| Entrada | Pode receber zero ou mais dados. |
| Saída | Deve produzir pelo menos um resultado. |
| Efetividade | Cada passo é elementar e executável em tempo finito. |

## Questão 2 — Algoritmo do cotidiano (2,5 pontos)

### 1. Algoritmo para trocar o pneu furado de um carro

1. Estacionar em local plano, puxar o freio de mão e ligar o pisca-alerta.
2. Retirar o estepe, o macaco e a chave de roda do porta-malas.
3. Afrouxar levemente os parafusos da roda furada com o carro ainda no chão.
4. Apoiar o macaco no ponto indicado e erguer o carro até a roda sair do chão.
5. Retirar os parafusos e a roda furada.
6. Instalar o estepe alinhando os furos de fixação.
7. Apertar os parafusos manualmente, em ordem cruzada.
8. Baixar o carro e retirar o macaco.
9. Apertar os parafusos com a chave de roda, novamente em ordem cruzada.
10. Guardar a roda furada, as ferramentas e conferir a pressão do estepe.
11. Fim.

### 2. Finitude e condição de fim

São 11 passos, quantidade fixa e finita. O término está definido no último passo: depois de apertar os parafusos, apoiar o carro no chão e guardar as ferramentas, o algoritmo termina. Não existe laço que possa continuar indefinidamente.

## Questão 3 — Raciocínio lógico e leitura atenta (2,5 pontos)

A cor dos olhos do motorista é a cor dos **meus próprios olhos**, porque o enunciado diz que *eu* estou dirigindo o ônibus.

O dado de entrada determinante é justamente a frase "Você está dirigindo um ônibus", que revela quem é o motorista. A quantidade de passageiros que entram e saem são dados distratores e não interferem na resposta.

## Questão 4 — Estruturas básicas e lógica (2,5 pontos)

### 1. Decisão × repetição

- **Decisão** (`se...então...senão`): avalia uma condição e segue apenas um dos caminhos, uma única vez por passagem.
- **Repetição** (`enquanto` / `para`): executa o mesmo bloco várias vezes enquanto a condição for verdadeira ou até atingir o limite definido.

Resumo: a decisão escolhe um caminho; a repetição executa o mesmo caminho várias vezes.

### 2. Pseudocódigo da soma de X e Y

```
ALGORITMO SomaXeY
INICIO
    LER X
    LER Y
    R <- X + Y
    ESCREVA R
FIM
```
