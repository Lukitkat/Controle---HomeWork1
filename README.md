# 1) Home Work 1:

Primeiro trabalho referente à disciplina de Controle da Universidade Federal do Ceará

## __Conceitos Abordados__

1.1) Transformada Inversa de Laplace: Cálculo manual utilizando a técnica de expansão em frações parciais para diferentes tipos de funções.

1.2) Verificação Computacional: Uso da biblioteca sympy do Python para validar os resultados obtidos manualmente.

1.3) Modos de Sistema: Determinação dos modos de um sistema a partir da equação característica de uma EDO.

1.4) Resposta de Sistemas: Cálculo da evolução livre (resposta a condições iniciais) e da resposta ao impulso.

1.5) Efeito de Polos e Zeros: Análise de como a posição de um zero afeta a resposta ao degrau e ao impulso de um sistema.

1.6) Aproximação de Sistemas: Determinação de uma aproximação de primeira ordem para um sistema de ordem superior.

1.7) Diagrama de Polos e Zeros: Construção e análise de diagramas de polos e zeros.

# 2) Home Work 2:

## __Conceitos Abordados__

1.1) Identificação de Sistemas: Obtenção de modelos de primeira e segunda ordem a partir de dados de resposta ao degrau.

1.2) Parâmetros de Resposta Transitória: Estimação de características como constante de tempo, tempo de acomodação, tempo de subida e porcentagem de overshoot.

1.3) Representação de Sistemas: Conversão de um modelo em espaço de estados para uma função de transferência.

1.4) Análise de Estabilidade: Estabilidade BIBO (Bounded-Input, Bounded-Output), Estabilidade de Lyapunov para sistemas LTI, Critério de Estabilidade de Routh-Hurwitz.

1.5) Lugar Geométrico das Raízes (Root Locus): Esboço e análise detalhada, incluindo pontos de cruzamento com o eixo imaginário, pontos de breakaway/break-in e assíntotas.

1.6) Erro em Regime Permanente: Cálculo do erro estacionário para diferentes entradas de teste (degrau, rampa e parábola).


# 3) Ferramentas Utilizadas:

__Linguagem__: Python

__Bibliotecas__:

  - pandas: Para carregar e manipular os dados dos arquivos .csv.
    
  - control: Biblioteca especializada para análise de sistemas de controle, usada para criar objetos de função de transferência e gerar os gráficos de Root Locus.
  
  - scipy.signal: Utilizada para criar funções de transferência e simular respostas de sistemas.
  
  - matplotlib.pyplot: Para toda a visualização de dados, incluindo respostas de sistemas e diagramas.
  
  - numpy: Para cálculos numéricos em geral.

  - sympy: Para cálculos simbólicos, especialmente a transformada inversa de Laplace.
