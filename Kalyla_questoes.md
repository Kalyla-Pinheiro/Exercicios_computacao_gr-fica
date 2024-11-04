# Enunciados

## DIA 13.08.2024 
## ASSUNTO : PREMISSAS GRÁFICAS

### 1- Desenvovler um procedimento para mapear uma representação formal de uma matriz armazenando o valor intensidade de brilho Y associado a cada uma delas.

algoritmo matrizBrilho

    inicio
        inteiro: m,n,i,j,Y[][],ValorBrilho
        leia(m,n,ValorBrilho)
        enquanto i < m faça
            equanto j < n faça
                i + 1
                j + 1
                ValorBrilho <- Y[i][j] 
                plotar(ValorBrilho)
            fimenquanto
        fimenquanto
    fim
    
### 2- Desenvolver um procedimento para provar qe uma imagem policromática é uma relação de um conjunto de imagem monocromática.
algoritmo policromatica

    inicio
        inteiro: imagemPolicromatica,r,g,b,

        leia(m,n,imagemPolicromatica)

        enquanto i < m faça
            enquanto j < n faça
                i + 1
                j + 1
                Y[i][j] <- R,G,B
                imagemPolicromatica = Y[i][j]
                plotar(Y[i][j])
            fimenquanto
        fimenquanto
    
        // criar imagens monocromaticas
        R' <- R
        G' <- G
        B' <- B
        
        imagemRecontruida <- R',G',B'

        se imagemPolicromatica = imagemRecontruida faça
            escreva("A imagem policromatica é formada por monocromaticas")
        fimse
    fim


### 3- Desenvolver um procedimento para caracterizar relações topológicas de objetos gráficos
algoritmo caracterizar_relacoes_topologicas

    inicio
        inteiro: x1,x2,x3,x4,x5,x6,y1,y2,y3,y4,y5,y6

        // considerando que eu tenho dois triangulos como os objetos

        leia(x1,x2,x3,x4,x5,x6,y1,y2,y3,y4,y5,y6)

        triangulo1<-v1v2,v2v3,v3v1
        triangulo2<-v4v5,v5v6,v6,v4

        se triangulo1 > triangulo2
            se (y2 = y5) e (x5 > x2) então
                    escreva("triangulo 2 está ao lado direito do triangulo 1")
            fimse
            se (y2 = y5) e (x5 < x2) então
                    escreva("triangulo 2 está ao lado esquerdo do triangulo 1")
            fimse
        fimse
    fim
    
### 4- Desenvolver uma pesquisa relacionada aos dispositivos físicos de i/o, bem como especificações físicas por dispositivos de processamento

## DIA 20.08.2024 - 22.08.2024 
## ASSUNTO : PRIMITIVAS GRÁFICAS

### 1- Desenvolver um procedimento em pseudocódgo para plotar um segmento de reta paralelo ao eixo das abcissas
  algoritmo segmento_retas_paralelas_abcissas
       
        inicio
            inteiro: xi,yi,xf,yf,pi,pf

            leia(xi,yi,xf,yf)

            se yi = yf então 
                se xf > xi então
                    plote(pi,pf)
                fimse
            fimse
        fim   

### 2-  Desenvolver um procedimento em pseudo-código ou português estruturado para plotar um segmento de reta paralela ao eixo das ordenadas, considerando dois ponto dados (Pi, Pf).
![image](https://github.com/user-attachments/assets/c28947c5-ee33-4b4c-afe4-bd75a061f646)

### 3 - Desenvolver um procedimento em pseudo-código ou português estruturado para plotar um segmento de reta paralela ao eixo das abscissas, considerando dois ponto dados (Pi, Pf).
é o mesmo só devo alterar a declaração das variáveis
![image](https://github.com/user-attachments/assets/1b66c611-6006-4bbe-bb8a-98d10ac9b9ab)

### 4 - Desenvolver um procedimento em pseudo-código ou português estruturado para plotar um segmento de reta paralela ao eixo das abscissas, considerando o ponto inicial (Pi) dado e como tamano de segmento de reta 40 posições.
nesse ele não pede o ponto final. Então será lido só o pontto inicial e com isso irá percorrer 40 posições e a última será dada como ponto final
![image](https://github.com/user-attachments/assets/6c6f8abb-9811-4df3-9851-e4af46eb80e4)

## PROBLEMAS DO DIA 29.08.2024
### 1- Desenvolver um procedimento em português estruturado ou pseudocódigo para plotar um quadrado no primeiro quadrante de sistema de eixo considere que v1, v2, v3 e v4 denominados vértices serão dados pelo usuário.
![image](https://github.com/user-attachments/assets/3a5ece85-5520-4c24-8ef9-63ff9a1cb630)

### 2- Desenvolver um procedimento em português estruturado ou pseudocódigo para plotar um retângulo no primeiro quadrante de sistema de eixo considere que v1, v2, v3 e v4 denominados vértices serão dados pelo usuário.
![image](https://github.com/user-attachments/assets/450d5341-10ca-4c95-82a2-f37fb4374776)
