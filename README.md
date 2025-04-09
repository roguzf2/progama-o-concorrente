# progamação-concorrente

Para rodar o programa basta seguir os seguintes passos:
  1. ./produto_interno arquivo_entrada <numero_de_threads>

  Caso queira trocar o vetor, basta:
    1. ./gerador <tamanho_do_vetor> arquivo_entrada
    2. ./produto_interno arquivo_entrada <numero_de_threads>

Algumas observações do experimento:
- Percebi que quanto mais threads eu coloco, menor é o erro (por mais que seja muito baixo já)
- Sinto que temos pouco erro pois temos uma situação onde cada thread calcula uma parte independente do produto. Se eu colocar um vetor com muitos elementos pode ser que encontre um erro relevante
