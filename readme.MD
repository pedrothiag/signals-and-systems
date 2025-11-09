# Sinais e Sistemas em Python

Esse repositório apresenta um conjunto de *notebooks* que abordam os conceitos fundamentais de Sinais e Sistemas explicados em Python.

## Descrição dos *notebooks*

### 1. ``01_numeros_complexos.ipynb``
Apresenta os principais conceitos de números complexos, incluindo as operações com números complexos e conversão entre formas de representação (polar, retangular).

### 2. ``02_sinais_sistemas.ipynb``
Introduz os conceitos iniciais sobre sinais e sistemas em tempo contínuo.
* Plotagem de sinais;
* Operações com sinais;
* Cálculo de energia;
* Relação de entrada-saída de sistemas de tempo contínuo;
* Cálculo da convolução de forma computacional;
* Solução de equações diferenciais ordinárias de forma simbólica;
* Análise de estabilidade de sistemas lineares e invariantes no tempo (LTI).

### 3. ``03_transformadas_de_laplace.ipynb``
Apresenta os principais conceitos sobre transformada de Laplace.
* Cálculo da transformada de Laplace direta e inversa utilizando cálculo simbólico;
* Análise de sistemas utilizando a transformada de Laplace utilizando cálculo simbólico;
* Cálculo da resposta ao impulso, degrau e forçada de forma numérica;
* Análise de interconexão de sistemas LTI;
* Exemplo de aplicação - análise de um motor de corrente contínua;
* Exemplo de aplicação - sistemas de controle.

### 4. ``04_series_transformada_fourier.ipynb``
Introduz os conceitos sobre as séries e transformada de Fourier em tempo contínuo.
* Cálculo numérico dos coeficientes da série trigonométrica, trigonométrica compacta e exponencial da série de Fourier em tempo contínuo;
* Cálculo numérico da transformada de Fourier em tempo contínuo;
* Cálculo da resposta em frequência de um sistema LTI;
* Aplicação - filtros seletivos em frequência;
* Aplicação - modulação em amplitude;
* Aplicação - multiplexação por divisão em frequência.

### 5. ``05_amostragem.ipynb``
Ilustra os conceitos da amostragem e reconstrução ideal.
* Amostragem e reconstrução ideal;
* Análise do efeito do *alising* em sinais senoidais.

## Referências

Alguns livros foram essenciais para a construção desse material. Os principais são:

* B.P. Lathi - Sinais e Sistemas Lineares. 2ª Edição. Bookman, 2006.

Livro-texto da disciplina. Apresenta os principais conceitos introdutórios sobre sinais e sistemas.

* B.P. Lathi - Signal Processing & Linear Systems. Berkeley Cambridge Press, 1998.

É um livro um pouco mais avançado do que o **Sinais e Sistemas Lineares** do mesmo autor. A ordem dos assuntos também é diferente (a transformada de Fourier é apresentada antes da transformada de Laplace).

* B.P. Lathi, R. A. Green - Essentials of Digital Signal Processing. Berkeley Cambridge Press, 2014.

Livro focado em processamento digital de sinais. Recomendável para uma primeira leitura, mas não para um detalhamento mais aprofundado sobre o assunto, porém apresenta a melhor introdução sobre filtros seletivos dos livros citados.

* B.P. Lathi, Z. Ding - Sistemas de Comunicações Analógicos e Digitais Modernos. 4ª Edição. LTC, 2012.

Livro focado em sistemas de comunicação. Recomendável para uma leitura no assunto sobre séries e transformadas de Fourier e suas aplicações. Apresenta uma interpretação de séries de Fourier utilizando decomposição de vetores, o que é particulamente interessante.

* A.V. Oppenheim, A.S. Willsky - Sinais e Sistemas. 2ª Edição. Pearson, 2010.

Livro clássico sobre Sinais e Sistemas. Apresenta muitas aplicações, porém pode ser um pouco indigesto para estudantes mais novatos. Todavia, apresenta uma bela discussão sobre sistemas de controle e sobre a utilização de transformadas bilaterais.

* A.V. Oppenheim, R. W. Schafer - Digital Signal Processing. Prentice Hall, 1975.

Livro focado em processamento digital de sinais. Quando colocado em conjunto com o livro do Lathi, formam um belo par de estudo. Embora antigo, ainda o recomendo como a primeira leitura da área.

* A.V. Oppenheim, R. W. Schafer - Processamento em Tempo Discreto de Sinais. 3ª Edição. Pearson, 2013.

É uma continuação "espiritual" do livro anterior. Alguns conceitos estão mais bem explicados neste texto (por exemplo, análise frequencial de sistemas em tempo discreto), porém em outros, o livro anterior é melhor (como, por exemplo, transformada $\mathcal{Z}$).