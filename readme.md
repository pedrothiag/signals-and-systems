# 🧮 Sinais e Sistemas

Esse repositório contém todos os materiais utilizados na disciplina de *Sinais e Sistemas* ministrada para o curso de Engenharia de Computação da UFERSA - Campus Pau dos Ferros.

## 📝 Para quê serve Sinais e Sistemas?

A disciplina de Sinais e Sistemas é um dos pilares fundamentais da Engenharia de Computação. Ela fornece a base matemática necessária para modelar e analisar fenômenos físicos que variam no tempo.

### 📍 Qual a sua importância?

Para a Engenharia de Computação, o conhecimento de Sinais e Sistemas reside em:

- Ponte entre Hardware e Software: Permite entender como sinais elétricos brutos se tornam dados processáveis.
- Fundamentação Matemática: Introduz ferramentas essenciais como a Transformada de Fourier, Transformada de Laplace e a Transformada $Z$, que são a base para o processamento de áudio, imagem e comunicações.
- Análise de Estabilidade: Essencial para garantir que sistemas de controle (como o de um drone ou um braço robótico) não se tornem instáveis e falhem.

### 🦾 Aplicações Práticas

1. Processamento Digital de Sinais (DSP): Envolve a filtragem de ruído em áudio, a compressão de arquivos (como MP3 e JPEG) e o reconhecimento de voz.
2. Telecomunicações e Redes: Toda a infraestrutura de Wi-Fi, 5G e comunicações via satélite baseia-se na modulação de sinais.
3. Visão Computacional e Processamento de Imagens: Uma imagem nada mais é do que um sinal bidimensional. Técnicas de realce de bordas, detecção de objetos em vídeos e filtros de redes sociais utilizam convoluções e filtragem de frequências espaciais.
4. Sistemas de Controle e Robótica: Sistemas embarcados em carros autônomos ou equipamentos médicos dependem de sistemas de realimentação (*feedback*). A análise de sinais permite que o controle desses sistemas.
5. Bioengenharia: A análise de sinais vitais, como o Eletrocardiograma (ECG) ou Eletroencefalograma (EEG), utiliza filtragem e análise espectral para identificar padrões de doenças ou monitorar a saúde de pacientes.

### 📐 Ferramentas Matemáticas

- Resposta ao impulso e Convolução
- Equações Diferenciais Ordinárias
- Transformada de Laplace
- Transformada $Z$
- Série de Fourier (em tempo contínuo e tempo discreto)
- Transformada de Fourier (em tempo contínuo e tempo discreto)


## 📅 Conteúdo Programático

Plano de Curso:

1. Números Complexos: [[Slides]](./slides/01_numeros_complexos.pdf) [[Notebook]](./notebooks/01_numeros_complexos.ipynb)
2. Sinais e Sistemas de Tempo Contínuo: [[Slides]](./slides/02_sinais_sistemas_tempo_continuo.pdf) [[Notebook]](./notebooks/02_sinais_sistemas.ipynb)
3. Análise no Domínio do Tempo de Sistemas de Tempo Contínuo: [[Slides]](./slides/03_analise_sistemas_tempo_continuo.pdf)
4. Transformada de Laplace: [[Slides]](./slides/04_transformada_de_laplace.pdf)
5. Série de Fourier em Tempo Contínuo: [[Slides]](./slides/05_serie_fourier_tempo_continuo.pdf)
6. Transformada de Fourier em Tempo Contínuo: [[Slides]](./slides/06_transformada_fourier_tempo_continuo.pdf)
7. Amostragem
8. Sinais e Sistemas de Tempo Discreto
9. Transformada $Z$
10. Série e Transformada de Fourier em Tempo Discreto

## 🐍 Utilização dos Códigos em Python

Para utilizar os códigos desenvolvidos na disciplina, recomenda-se:

- Criar um ambiente virtual Python para a instalação das dependências:

```bash
python3 -m venv ./virtual-env
```

Após isso, habilitar o ambiente virtual:

```bash
source ./virtual-env/bin/activate
```

- Instalar os seguintes pacotes:

```bash
pip install numpy scipy pandas matplotlib notebook sympy
```

- Para rodar o Jupyter Notebook, basta executar o seguinte comando na pasta aonde o arquivo do notebook esteja localizado:

```bash
python3 -m notebook
````

## Avaliações

| Semestre | Unidade 1 | Unidade 2 | Unidade 3 | Recuperação |
| -------- | --------- | ----------| --------- | ----------- |
| 2026.1   | [[P1]](./avaliacoes/2026_1/p1.pdf) | | | |
| 2025.2   | [[P1]](./avaliacoes/2025_2/p1.pdf) | [[P2a]](./avaliacoes/2025_2/p2a.pdf) [[P2b]](./avaliacoes/2025_2/p2b.pdf) | [[P3]](./avaliacoes/2025_2/p3.pdf) | [[Recuperação]](./avaliacoes/2025_2/rec.pdf) |
| 2025.1 | [[P1]](./avaliacoes/2025_1/p1.pdf) | [[P2]](./avaliacoes/2025_1/p2.pdf) | [[P3]](./avaliacoes/2025_1/p3.pdf) | [[Recuperação]](./avaliacoes/2025_1/rec.pdf) |
