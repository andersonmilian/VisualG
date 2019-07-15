# VisualG 😎
![VisualG_Version](https://img.shields.io/badge/VisualG-3.0-orange.svg)

Aqui irei colocar todos os códigos praticados na **UC09 - Lógica de Programação**, que estudei no Senac VPR 

## A Tela Principal do VisualG
![60443652-12202c00-9bf2-11e9-947c-614f8ac883f0](https://user-images.githubusercontent.com/52283944/60517445-16158200-9cb6-11e9-9afe-11c1a4e8c06c.png)

O programa é muito simples e possui uma interface amigável. Para completar, ele está totalmente em português, o que ajuda muito quem não tem familiaridade com o inglês.

Contém os comandos mais utilizados no Visualg (estes comandos também podem ser acessados pelo menu ou por atalhos no teclado).

### Barras de Ferramentas
![image002](https://user-images.githubusercontent.com/52283944/60590976-bbdaf680-9d73-11e9-9fe2-27bc66051409.gif)

1 - **Novo (Ctrl-N)** : Cria um novo "esqueleto" de algoritmo, substituindo o texto existente no editor. Se este tiver sido modificado, o Visualg pedirá sua confirmação para salvá-lo antes que seja sobreposto.

2 - **Abrir (Ctrl-A)** - Abre um algoritmo anteriormente gravado, substituindo o texto existente no editor. Se este tiver sido modificado, o Visualg pedirá sua confirmação para salvá-lo antes que seja sobreposto.

3 - **Salvar (Ctrl-S)** - Salva imediatamente o texto do editor. Caso seja a primeira vez que um novo texto é gravado, o Visualg pedirá o seu nome e localização.

4 - **Imprimir** - Imprime imediatamente o texto existente no editor. Para configurar a impressão, use o comando Imprimir... do menu Arquivo (acessível também pelo atalho Ctrl-P).

5 - **Recortar** – Move um texto selecionado para a memória.

6 - **Copiar** – Copia um texto selecionado para a memória.

7 - **Colar** – Retira conteúdo da memória e coloca no local do cursor.

8 - **Gravar** Bloco – Abre uma janela para salvar o bloco selecionado. Objetivo é criar uma espécie de biblioteca de funções.

9 - **Inserir** um bloco – Insere um bloco arquivado no local do cursor.

10 e 11 - **Desfazer e refazer** – Desfaz e refaz ação criada no editor de texto.

12 - **Localizar** – Abre uma janela para você digitar a palavra que deseja localizar no Editor de textos.

13 - **Substituir** – Abre uma janela para você poder digitar a palavra que deseja localizar e substituir no Editor de textos.

14 - **Corrigir Indentação (Ctrl-G)** - Corrige automaticamente a indentação do "código-fonte", colocando os comandos dentro de uma estrutura de 3 colunas à direita da coluna inicial da estrutura conforme a configuração padrão.

15 - **Numerar Linhas** - Liga/desliga a exibição dos números das linhas na área à esquerda do editor. A linha e coluna do editor em que o cursor está em um determinado momento também são mostradas na primeira parte da barra de status, situada na parte inferior da tela. Os números de linhas, caso ligados, são desligados durante a execução do algoritmo por motivos técnicos, mas são ligados de volta ao fim do "programa".

16 - **Mostra Variáveis Modificadas** - Liga/desliga a exibição da variável que está sendo modificada. Como o número de variáveis pode ser grande, muitas podem estar fora da janela de visualização; quando esta característica está ligada, o programa rola a grade de variáveis de modo que aquela que está sendo modificada no momento fique visível. Útil quando se está executando o algoritmo passo a passo. Por questões de performance, o valor padrão desta característica é desligada quando o algoritmo está sendo executado automaticamente, mas se você clicar este botão pode executar o algoritmo automaticamente com a exibição ligada. O valor volta automaticamente para desligada ao fim da execução.

17 - **Restaura a tela inicial do Visualg** – Retorna a tela original do programa.

## Barra de Execução de Algoritmos

![image005](https://user-images.githubusercontent.com/52283944/60671918-92d96500-9e4a-11e9-89be-ae13ff294218.jpg)

1 - **Executar** (F9) - **Inicia** (ou continua) a execução automática do algoritmo.

2 - **Tempo por linha** (shift + F9) – Executa o algoritmo linha por linha automaticamente determinado por um tempo escolhido pelo o usuário.

3 - **Passo** (F8) - Inicia (ou continua) a execução do algoritmo linha por linha, dando ao usuário oportunidade de acompanhar o fluxo do programa, examinar variáveis, etc.

4 - **Parar** (Ctrl-F2) - Termina imediatamente a execução do algoritmo. Este botão fica desabilitado quando o algoritmo não está sendo executado.

5 - **Marca e Desmarca um Breakpoints** (F5) – Cria pontos de parada. Selecione a linha que deseja criar um ponto de parada na hora de execução do algoritmo e pressione o Breakpoints surgirá uma linha marrom e um marcador do lado esquerdo para indicar o ponto de parada. Para desmarcar o ponto de parada basta selecionar a linha que possui o breakpoint e clicar no mesmo. O breakpoints não funciona no modo passo a passo e para continuar o algoritmo depois de uma parada pressione novamente o F9 ou o botão Executar.

6 - **Desmarca todos os BreakPoints** (CTRL+F5)

7 - **Executa em Modo Dos** – Quando ativado durante a execução do algoritmo ele executa o algoritmo em uma janela em modo dos.

8 - **Gerador valores** – Substitui digitação do usuário por um sistema de geração aleatória de valores numéricos e caracter (este comando não afeta a leitura de variáveis do tipo lógico - com certeza uma coisa pouco usual...). Gera números e caracteres aleatoriamente, muito útil para não perder tempo pensando o que digitar, você escolhe o inicio e o fim dos valores e se for valores com casas decimais é só escolher quantas casas decimal você quer.

9 - **Perfil** (F7) - Mostra, após a execução de um algoritmo, quantas vezes cada linha foi executada. Útil para a análise de eficiência de um algoritmo, como por exemplo, nos métodos de classificação.

10 - **Pilha** (CTRL+F3) - Mostra a pilha de ativação do programa (call stack), com o nome dos procedimentos e funções chamados, nome, tipo e valor dos parâmetros.

11 - __Ajuda on-line__ (F1).

## Visualizador De Variáveis

Contém uma grade onde são mostrados: Escopo da variável (Global quando nome da variável for global ou o nome da função ou Procedimento quando for local). O Nome da variável (com índice ou índices, caso seja um elemento de um vetor), seu Tipo ("R" para Real, “I” para Inteiro, "C" para literal e "L" para lógico), e o seu Valor corrente. A versão atual do Visualg permite até 500 variáveis (cada elemento de um vetor conta como uma variável).
Também, de acordo com o tipo de parâmetro a cor no grid muda, e para os parâmetros passados por referência. Há uma seta que mostra o nome da variável que eles representam fora do subprograma. Isto tudo, naturalmente, só pode ser visto se executarmos o algoritmo passo a passo...

![image006](https://user-images.githubusercontent.com/52283944/60673548-5c054e00-9e4e-11e9-9b79-067ed16c56ad.gif)

## Simulador de Saída

Mostra o resultado do algoritmo, invés de executar no modo dos, você pode verificar a saída do algoritmo aqui no simulador de saída.

![image007](https://user-images.githubusercontent.com/52283944/60673566-69223d00-9e4e-11e9-89f3-69c53b055ced.jpg)

## A Barra De Status

Mostra o resultado do algoritmo, invés de executar no modo dos, você pode verificar a saída do algoritmo aqui no simulador de saída.

![image008](https://user-images.githubusercontent.com/52283944/60673608-8525de80-9e4e-11e9-96db-751e2f197982.gif)


![NextEmbellishedHerald-size_restricted](https://user-images.githubusercontent.com/52283944/61215359-05ff9880-a6e1-11e9-84d8-2f11ec307315.gif)