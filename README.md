# textsmanipulating  
PARA O PYTHON TODA CADEIA DE CARACTERS ESTA ENTRE ASPAS SIMPLES OU DUPLAS '', "".
'DANIELLA' <- É UM STRING 
NESSE MODEULO VAMOS APRENDER A MANIPULAR ESSA CADEIA DE CARACTERS 

ANALISE
len(frase) #comprimento da string
frase.count('o') #contar quantas vezes aparecere a letra entre aspas na string, 
caso queira usar o fatiamneto para especificar, vai contar de 0 a 12, pois a ultima e ignorada pelo python
frase.count('o',0,13) 
frase.find('deo') #quantas vezes ele encontrou o que esta entre aspas.
se eu coloco dentro do find alguma string q nao existe ele ira retornar -1
' xx ' in frase # existe o que esta entre aspas na minha frase 

TRANSFORMAÇÃO
frase.replace('python', 'android') # onde esta a palavra python ela vai ser substituida por android
frase.upper() #em maisculas o que ainda nao esta
frase.lower() #em minusculo o que esta em maiusculo
frase.capitalize() #jogar todos para minusculos e so o primeiro vai ficar me maiusculo
frase.title() #vai analisar toda a string e o que esta depois do espaço ele colocora em maiusculo
frase.strip() #remover espaços inuteis
frase.rstrip() #ira remover somente os espaços da direita
frase.lstrip() #ira remover somente os espaços da esquerda

DIVISÃO
frase.split() #vai pegar onde estiver espaços e criar uma divisão, refazendo os indices e criando nocas listas
'-'.join(frase) # vou juntar todos os elementos da frase e utilizar o - nos locais onde haveia espaço, posso usar outro caracter tbm 

