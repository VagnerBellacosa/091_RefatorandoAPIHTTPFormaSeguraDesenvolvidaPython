[
python](https://programadoresbrasil.com.br/category/linguagens-de-programacao/python/?amp)

[Veja 10 dicas para Programar em Python](https://programadoresbrasil.com.br/2020/05/programar-em-python-dicas/?amp)

11 de maio de 2020 \- 7 Min de Leitura



![img](data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjM2NSIgd2lkdGg9IjU4OCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB2ZXJzaW9uPSIxLjEiLz4=)![Dicas sobre como programar em Python - No mundo de hoje, o Python é uma das linguagens mais usadas. Não é apenas uma linguagem, é uma maneira de fazer as coisas de maneira adequada, simples e compacta. ](https://cdn.programadoresbrasil.com.br/wp-content/uploads/2020/05/python1.jpg)

**Dicas sobre como programar em Python –** No mundo de hoje, o Python é uma das linguagens mais usadas. Não é apenas uma linguagem, é uma forma de fazer as coisas de maneira adequada, simples e compacta. 

Python é [uma das linguagens](https://programadoresbrasil.com.br/2020/04/linguagens-programacao-mais-usadas/?amp)(conheça as 5+) de alto nível mais conhecidas, especialmente em código aberto. A programação Python é uma linguagem rápida, compacta e que pode ser facilmente renderizada em qualquer sistema operacional. 

Além disso, se você olhar em volta, verá que a maioria das coisas roda em Python; você pode pegar exemplos do Google ou YouTube; Facilmente será atraído a um **curso em vídeo python.**

Portanto, esses são alguns truques que valem a pena ter salvos em algum arquivo de texto se você pensa em **programar em python**.

Sempre que estiver preso a qualquer parte do código, apenas vislumbre essas coisas e a maioria dos seus problemas serão solucionados muitas vezes.

## Dicas para Programar em Python

[mostrar_anuncio_vitrine_responsiva_lomadee]

### 1. Módulos

A melhor coisa de **programar em python** é que você pode criar seus próprios módulos. Por exemplo, posso criar minha própria função e módulos e colocá-los todos juntos em uma pasta separada.

Então, o que faço é escrever códigos específicos, que sei que usaria em comum na maior parte do meu trabalho, depois convertê-los em um módulo e mantê-los em uma pasta separada.

Ao fazer isso, economizo muito tempo, escrevendo-os novamente e depurando-os para verificar se há erros. Outro motivo para isso é que você precisa manter seu programa eficiente e gerenciável, se eles forem grandes em tamanho.

Portanto, para gerenciar isso, você pode dividi-los em arquivos separados, colocar várias funções e definições em um arquivo e usá-las importando-as para scripts e programas.

Observe que esses arquivos terão uma extensão * .py. E depois de importá-los, ele criará automaticamente um *.

### 2. Verdadeiro e falso

Este também é um dos métodos mais usados. Se você já jogou, e por jogos, quero dizer Jogos de última geração, você deve ter notado que às vezes é necessário diminuir os gráficos.

Mas, novamente, às vezes, mesmo você não consegue encontrar essas opções no jogo. Então, o que você normalmente faz é encontrar o arquivo de configuração na pasta de documentos e alterá-lo.

Por exemplo, você altera Vsync = True ou False conforme a situação. Mas o que estou tentando explicar aqui é um pouco diferente, mas ainda está relacionado a ele. Verdadeiro é igual a 1 e Falso é igual a 0 em python.

Em resumo, verdadeiro significa que você concorda e falso significa que você não concorda. Essas coisas são usadas com mais freqüência em python.

Portanto, você pode atribuir instruções True e False usando o sinal “=” ou verificar a igualdade usando o sinal “==”. Tão simples como isso.

### 3. Depuração de desempenho do Python

![img](data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjM2MCIgd2lkdGg9IjUzNyIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB2ZXJzaW9uPSIxLjEiLz4=)![Ao escrever um programa, nosso principal objetivo é tornar o programa eficiente, rápido e compacto. Mas há momentos em que você simplesmente não pode compactar o programa.](https://cdn.programadoresbrasil.com.br/wp-content/uploads/2020/05/python6.jpg)

Ao escrever um programa, nosso principal objetivo é tornar o programa eficiente, rápido e compacto. Mas há momentos em que você simplesmente não pode compactar o programa.

Por isso, nesses momentos, você pode não querer compactar o programa para torná-lo mais rápido. O que você pode fazer é, por exemplo, ao manipular códigos em um dicionário, você pode tentar um método alternativo de ditar um item. Confuso? Deixe-me explicar isso.

Você pode simplesmente escolher uma opção para adicionar um item diretamente e depois verificar se os itens inseridos existem ou precisam ser atualizados. 



Dessa maneira, ao fazer isso, você não precisa verificar todos os outros itens para corresponder a ele e atualizá-lo, o que tornará o aplicativo lento. A seguir, um exemplo famoso disso:

```
*p = 16*
*myDiction = {}*
*for i in range(0, p):*
*char = 'abcd'[i%4]*
*if char not in myDict:*
*myDiction[char] = 0*
*myDiction[char] += 1*
*print(myDiction)*
```

O exemplo acima é a maneira normal de escrevê-lo. Agora, veja como ele fará o código rodar mais rápido,


`*p = 16
myDiction = {}
for I in range(0, p):
char = ‘abcd’[i%4] try:
myDiction[char] += 1
except KeyError:
myDiction[char] = 1
print(myDiction)*`

### 4. Py2exe para programar em python

Outra dica útil que consigo pensar é o py2exe. Normalmente, ao escrever um código em qualquer idioma, às vezes pode ser um incômodo compilá-lo em um executável, especialmente se você estiver usando o Windows.

Mas quando se fala em **programar em python**, é realmente muito simples. Você pode simplesmente baixar o py2exe, que novamente é um software de código aberto que pode ser baixado no sourceforge.net.

[mostrar_anuncio_vitrine_responsiva_lomadee]

Usando este aplicativo, você pode simplesmente converter até seus módulos em um exe, ao contrário de [C](https://www.educba.com/course/c-training-bundle/) ou [C ++,](https://www.educba.com/course/online-c-plus-plus-programming-training/) que é realmente um estresse mental ao compilar um exe.

### 5. Conjuntos

Se você é um fanático por matemática, certamente adoraria esta próxima dica. Você pode ter usado conjuntos nas classes mais baixas. Lembra de algo? Sim, exatamente, sindicatos e outras coisas.

Então, existem pessoas como eu, que às vezes não gostam de usar software automatizado. A razão para isso é segurança. Vamos dar um exemplo simples do [Microsoft Excel](https://www.microsoft.com/pt-br/microsoft-365/excel) .

Algumas pessoas tendem a usar o Excel, apenas para agrupar e criar um banco de dados. Eles só precisam disso e de uma boa segurança para isso.Eles não estão interessados em formatar o texto, cor e outras coisas.

Então, o que faço naquele momento é criar minha própria pilha de softwares de programação python e criar meu próprio banco de dados. Por alguns dos meus motivos de segurança, prefiro o Python ao invés do MYSql.

Assim, voltando ao meu ponto de conjuntos, os conjuntos são extremamente úteis ao criar bancos de dados. Especialmente, quando você deseja encontrar correspondências, crie grupos e outras tarefas semelhantes. A seguir, é apresentado um exemplo simples disso.

```
*>>> A = {1, 2, 3, 3}
\>>> A
set([1, 2, 3])
\>>> B = {3, 4, 5, 6, 7}
\>>> B
set([3, 4, 5, 6, 7])
\>>> A | B
set([1, 2, 3, 4, 5, 6, 7])
\>>> A & B
set([3])
\>>> A - B
set([1, 2])
\>>> B - A
set([4, 5, 6, 7])
\>>> A ^ B
set([1, 2, 4, 5, 6, 7])
\>>> (A ^ B) == ((A - B) | (B - A))
True*
```

### 6. Mesclando scripts Python e Shell

![img](data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjM2MCIgd2lkdGg9IjUzNyIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB2ZXJzaW9uPSIxLjEiLz4=)![Agora isso é algo que você não pode fazer com C ou C ++ . Se você é um cara de código aberto, certamente usaria o Linux  como o sistema operacional principal ou pelo menos uma inicialização dupla.](https://cdn.programadoresbrasil.com.br/wp-content/uploads/2020/05/python4.jpg)

Agora isso é algo que você não pode fazer com C ou C ++ . Se você é um cara de código aberto, certamente usaria o Linux como o sistema operacional principal ou pelo menos uma inicialização dupla.

Portanto, o Linux já inclui python . E python é extremamente compatível com Linux. Isso nos dá o benefício de compilar e mesclá-los.

Você pode simplesmente criar um script que possa funcionar como um script unix normal , bem como um código python interpretado ao mesmo tempo.



Ao escrever um script de shell, você precisa de quatro caracteres de aspas e uma string vazia no shell, mas em python, é necessário fazer isso com uma string de aspas triplas com um caractere de aspas.

Lembre-se de que a primeira cadeia de caracteres de um script pode ser facilmente armazenada como uma cadeia de documentos de um módulo, mas depois disso, o interpretador python simplesmente a ignora.
O exemplo é o seguinte:

```
*#!/bin/sh
__doc__ = """
Demonstrate how to mix Python + shell script.
"""
import sys
print "Hello World!"
print "This is Python", sys.version
print "This is my argument vector:", sys.argv
print "This is my doc string:", __doc__
sys.exit (0)*
```

### 7. estilo JSON

Python tem muitas coisas ocultas por baixo. Leva apenas uma pessoa e seu tempo para descobrir o que todos os operadores e coisas mágicas estão escondidos lá dentro.

Um entre todas as outras coisas é o famoso estilo JSON. Você pode criar dicionários aninhados sem criar explicitamente subdicionários. Eles magicamente passam a existir quando os referimos.


Exemplo da seguinte maneira: Agora você pode imprimir o acima como JSON com:


`*users = tree()
users['harold']['username'] = 'hrldcpr'
users['handler']['username'] = 'matthandlersux'
*`

```
*>>>print(json.dumps(users))*
```

E ficará assim:
`*{"harold": {"username": "hrldcpr"}, "handler": {"username": "matthandlersux"}}*`

[mostrar_anuncio_vitrine_responsiva_lomadee]

### 8. Pip para programar em python

Pip é algo que talvez a maioria das pessoas conheça. Mas ainda assim, é uma coisa incrível que você precisa saber se está começando com **python basico.**

Às vezes, você precisa inspecionar a fonte de um pacote antes de instalá-lo. Na maioria das vezes, é para instalar uma versão mais recente de algum pacote. Portanto, você pode simplesmente instalar o pip e fazer o seguinte:

`*>>> pip install --download sqlalchemy_download sqlalchemy
\>>>pip install --no-install sqlalchemy
\>>>pip install --no-download sqlalchemy*`
Se você deseja instalar a versão mais recente de um pacote, você pode verificá-la diretamente no repositório GIT.

```
*>>>pip install git+https://github.com/simplejson/simplejson.git
\>>>pip install svn+svn://svn.zope.org/repos/main/zope.interface/trunk*
```

### 9. Virtualenv

![img](data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjM2MCIgd2lkdGg9IjUzNyIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB2ZXJzaW9uPSIxLjEiLz4=)![programar em python](https://cdn.programadoresbrasil.com.br/wp-content/uploads/2020/05/python5-1.jpg)

Outra função importante do python é o Virtualenv. Virtualenv significa ambiente virtual. Agora, meus amigos, é uma função muito impressionante do python. Basicamente, para testar o python em diferentes condições, você normalmente precisaria alterar o ambiente global do python.



Porém, um dos principais benefícios do armazenamento em sandbox em seu ambiente python é que você pode testar facilmente um código em diferentes versões e dependências de pacotes do python .

Para instalar o virtualenv, você precisa instalar o pip primeiro.
Você pode fazer o seguinte:

```
*easy_install pip
pip install virtualenv
virtualenv python-workspace
cd python-workspace
source ./bin/activate
python*
```

### 10. Zen of Python para programar em python

Por último, mas não menos importante, é o Zen of python. Zen of python é um mini-guia para você **aprender a programar em python** começando do **python basico**. Simplesmente vá ao interpretador python e digite:

```
*>>>import this*
```

E eu não vou explicar este. Porque é simplesmente incrível experimentar você mesmo.

E agora, chegamos ao fim do caminho. Essas são apenas minhas experiências, mas se você encontrar algumas, com certeza as publique para que o mundo saiba exatamente como o python é impressionante.