# Enunciados

## DIA 13.08.2024 
## ASSUNTO : PREMISSAS GRÁFICAS

## BASEADO NA ESPECIFICAÇÃO DAS PREMISSAS GRÁFICAS DESENVOLVER OS SEGUINTES PROCEDIMENTOS EM PSEUDOCÓDIGO OU PORTUGUÊS ESTRUTURADO.

### 1- Desenvovler um procedimento para mapear uma representação formal de uma matriz armazenando o valor de intensidade de brilho Y associado a cada uma delas.

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
    
### 2- Desenvolver um procedimento para provar que uma imagem policromática é uma relação de um conjunto de imagem monocromática.
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
    
### 4- Desenvolver uma pesquisa relacionada aos dispositivos físicos de i/o gráficos, bem como especificações físicas por dispositivos de processamento

## DIA 20.08.2024 - 22.08.2024 
## ASSUNTO : PRIMITIVAS GRÁFICAS

### 5- Desenvolver um procedimento em pseudocódgo para plotar um segmento de reta paralelo ao eixo das abcissas
algoritmo segmento_retas_paralelas_abcissas

        inicio
            inteiro: xi,yi,xf,yf,pi,pf

            leia(xi,yi,xf,yf)

            se yi = yf e xf > xi então 
               para i de xi até xf faça
                    i + 1
                    plotar(pipf)
                fimpara
            fimse
        fim  
### 6-  Desenvolver um procedimento em pseudo-código ou português estruturado para plotar um segmento de reta paralela ao eixo das ordenadas, considerando dois pontos dados (Pi, Pf).
algoritmo segmento_retas_paralelas_ordenadas
        
        inicio
            inteiro: xi,yi,xf,yf,pi,pf

            leia(xi,yi,xf,yf)

            se xi = xf e yf > yi então 
               para i de yi até yf faça
                    i + 1
                    plotar(pipf)
                fimpara
            fimse
        fim  

### 7 - Desenvolver um procedimento em pseudo-código ou português estruturado para plotar um segmento de reta paralela ao eixo das abscissas, considerando dois pontos dados (Pi, Pf).
algoritmo segmento_retas_paralelas_abcissas
      
        inicio
            inteiro: xi,yi,xf,yf,pi,pf

            leia(xi,yi,xf,yf)

            se yi = yf e xf > xi então 
               para i de xi até xf faça
                    i + 1
                    plotar(pipf)
                fimpara
            fimse
        fim  

### 8 - Desenvolver um procedimento em pseudo-código ou português estruturado para plotar um segmento de reta paralela ao eixo das abscissas, considerando o ponto inicial (Pi) dado e como tamanho de segmento de reta 40 posições.

  
    inicio
        inteiro: xi,yi,tamanho,pi,pf

        tamanho <- 40
        leia(xi,yi)

        xf <- xi + tamanho - 1
        yf <- yi

        se (yi = yf) e (xf >xi) entao
            para i de xi até xf faça
                i+1
                plotar(pipf)
            fimpara
        fimse
    fim

## PROBLEMAS DO DIA 27.08.2024

### 9- Desenvolver um procedimento em pseudocódigo ou português estruturado para plotar um segmento de reta entre dois pontos dados: Pi, Pf.Considere a possibilidade do segmento estar em uma das seguintes posições:
#### a) Paralela ao eixo das abcissas
#### b) Paralela ao eixo das ordenadas
#### c) Em diagonal perfeita

## PROBLEMAS DO DIA 29.08.2024
### 10- Desenvolver um procedimento em português estruturado ou pseudocódigo para plotar um quadrado no primeiro quadrante de sistema de eixo considere que v1, v2, v3 e v4 denominados vértices serão dados pelo usuário.


### 11- Desenvolver um procedimento em português estruturado ou pseudocódigo para plotar um retângulo no primeiro quadrante de sistema de eixo considere que v1, v2, v3 e v4 denominados vértices serão dados pelo usuário.

## PROBLEMAS DO DIA 05.09.2024
### 12- Desenvolver um procedimento em pseudocódigo ou em português estruturado para plotar um feixe de N retas paralelas ao eixo das abcissas. Considere dois pontos dados Pi, Pf e uma distância d entre as retas.

### 13- Desenvolver um procedimento em pseudocódigo ou em português estruturado para plotar um feixe de N retas paralelas ao eixo das oredenadas. Considere dois pontos dados Pi, Pf e uma distância d entre as retas.

## QUESTÕES DO DIA 17.09.2024
### 14- Questões de pesquisar o artigo
#### a) Explique a relação entre inteligência artificial e o processamento digital da imagem, como usa possível solução tecnológica para o problema abordado no texto de LTA.
#### b) Explique o que é um processo de indexação de imagem dgital utilizando coordenadas geográficas. Dê um exemplo considerando um banco de dados geográficos.

## QUESTÕES DO DIA 24.09.2024
### 15- Desenvolver um procedimento para plotar um setor circular disposto sobre o primeiro quadrante. Considere que o mesmo está centrado na origem.

### 16- Desenvolver um procedimento para plotar um semi-círculo centro na origem, considere que o mesmo está disposto sobre o 1º e 2º quadrante. Utilize a técnica de simetria. Conforme preconizado por Bresenhan,20000.

### 17- Explique de que forma a transposição dos eixos gráficos possibilitando a geração de objetos planos. Dê um exemplo.
