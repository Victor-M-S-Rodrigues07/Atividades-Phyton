# <h1 align = "center"> Lista de Exercícios - Árvores - Estrutura de Dados II </h1>

<div align = "center">
<img src = ".\imgs\imagem-capa.png" alt = "Imagem do site" height = "400">
</div>

### Status da Lista: Concluída ✔

## 🗂 Sumário

- [📝 Descrição da Lista](https://github.com/Victor-M-S-Rodrigues07/Atividades-Arvores-Simples-BST-AVL--Lista-de-Exercicios-N3-2025#-descri%C3%A7%C3%A3o-da-lista)
- [🎯 Objetivos da Lista](https://github.com/Victor-M-S-Rodrigues07/Atividades-Arvores-Simples-BST-AVL--Lista-de-Exercicios-N3-2025#-objetivos-da-lista)
- [💻 Tecnologias Utilizadas](https://github.com/Victor-M-S-Rodrigues07/Atividades-Arvores-Simples-BST-AVL--Lista-de-Exercicios-N3-2025#-tecnologias-utilizadas)
- [📂 Estrutura doS Arquivos](https://github.com/Victor-M-S-Rodrigues07/Atividades-Arvores-Simples-BST-AVL--Lista-de-Exercicios-N3-2025#-estrutura-dos-arquivos)
- [Exercício Nº 1: 🌳 Árvore](https://github.com/Victor-M-S-Rodrigues07/Atividades-Arvores-Simples-BST-AVL--Lista-de-Exercicios-N3-2025#-exerc%C3%ADcio-n%C2%BA-1--%C3%A1rvore-)
- [Exercício Nº 2: 0️⃣1️⃣ Árvore Binária de Busca (BST)](https://github.com/Victor-M-S-Rodrigues07/Atividades-Arvores-Simples-BST-AVL--Lista-de-Exercicios-N3-2025#-exerc%C3%ADcio-n%C2%BA-2-0%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A3-%C3%A1rvore-bin%C3%A1ria-de-busca-bst-)
- [Exercício Nº 3: ⚖ BST com Balanceamento](https://github.com/Victor-M-S-Rodrigues07/Atividades-Arvores-Simples-BST-AVL--Lista-de-Exercicios-N3-2025#-exerc%C3%ADcio-n%C2%BA-3--bst-com-balanceamento-)
- [Exercício Nº 4: 🌲 Árvore AVL](https://github.com/Victor-M-S-Rodrigues07/Atividades-Arvores-Simples-BST-AVL--Lista-de-Exercicios-N3-2025#-exerc%C3%ADcio-n%C2%BA-4--%C3%A1rvore-avl-)
- [Exercício Nº 5: ⚡ Treino da AVL](https://github.com/Victor-M-S-Rodrigues07/Atividades-Arvores-Simples-BST-AVL--Lista-de-Exercicios-N3-2025#-exerc%C3%ADcio-n%C2%BA-5--treino-da-avl-)
- [✨Autor](https://github.com/Victor-M-S-Rodrigues07/Atividades-Arvores-Simples-BST-AVL--Lista-de-Exercicios-N3-2025#-autor)
- [📞 Contatos](https://github.com/Victor-M-S-Rodrigues07/Atividades-Arvores-Simples-BST-AVL--Lista-de-Exercicios-N3-2025#-contatos)

## 📝 Descrição da Lista

Essa lista de exercícios foi criada com o intuito de testar e aplicar os conceitos de Árvores, Árvores Binárias de Busca, AVLs, entre outros conceitos apresentados na disciplina de **Estrutura de Dados II**, lecionada pelo profº Agnei de Carvalho Silva. Ela é composta por **5 (cinco)** exercícios, cada um contendo um tipo de árvore, começando pela simples até a mais complexa. <br>

Por sua simplicidade e velocidade, foi escolhida a linguagem de Programação **Python** para a resolução e criação das árvores. Também foi utilizada a biblioteca **grapviz** para o diagrama de ilustração. <br>

## 🎯 Objetivos da Lista

- Fixar os conceitos estruturais básicos;
- Dominar os Algoritmos de Percurso (Caminhamento);
- Desenvolver a lógica de inserção e remoção manual;
- Compreender e aplicar Rotações de Balanceamento (AVL);
- Analisar a complexidade de tempo e espaço usando a Notação Big-O;
- Implementar algoritmos recursivos;
- Resolver problemas de aplicação prática. <br>

## 💻 Tecnologias Utilizadas

![Jupiter Notebook](https://img.shields.io/badge/Jupiter_Notebook-0?style=for-the-badge&logo=jupyter&logoColor=white&labelColor=%23F27329&color=%23F27329)
![Python](https://img.shields.io/badge/Python-0?style=for-the-badge&logo=python&logoColor=%23FFFFFF&color=%233776AB)
![Git](https://img.shields.io/badge/Git-0?style=for-the-badge&logo=git&logoColor=%23FFFFFF&color=%23F05032)
![GitHub](https://img.shields.io/badge/GitHub-0?style=for-the-badge&logo=github&logoColor=%23FFFFFF&color=%23181717) <br>

## 📂 Estrutura dos Arquivos

```
/imgs

/Atividade-1
    Atividade-1.ipynb
    tree_fixed.png
    tree_random.png

/Atividade-2
    Atividade-2.ipynb
    arvore_bst.png
    arvore_bst_2.png
    arvore_bst_3.png

/Atividade-3
    Atividade-3.ipynb
    arvore_bst.png
    arvore_bst_random.
    
/Atividade-4
    Atividade-4.ipynb
    arvore_avl.png
    arvore_avl1.
    arvore_avl2.png
    arvore_avl3.png
    arvore_avl4.png
    arvore_avl5.png
    arvore_avl6.png
    arvore_avlRandom.png

/Atividade-5
    Atividade-5.ipynb

README.md
```

## <h2 align = "center"> Exercício Nº 1: 🌳 Árvore </h2> <br>

<div align = "center">

<img src = ".\Atividade-1\tree_fixed.png" width = 400px alt = "Imagem da árvore com números e operadores dentro dos seus nós">

O primeiro exercício diz repeito a criação de uma árvore comum, onde cada nó folha representa um número, enquanto os outros representam os operadores. O algoritmo segue a percursão *in-order*, identificando os dois números e a operação selecionada, resolvendo-a e armazenando o resultado, até se chegar à raiz, onde imprime a solução no console.

</div>

## <h2 align = "center"> Exercício Nº 2: 0️⃣1️⃣ Árvore Binária de Busca (BST) </h2> <br>

<div align = "center">

<img src = ".\Atividade-2\arvore_bst_3.png" width = 400px alt = "Imagem da árvore binária, onde os números menores ficam à esquerda do nó e os maiores ficam à direita">

Esse exercício se refere ao conceito de Árvore Binária de Busca (Binary Search Tree -- BST). A BST tem por regra que números miores do que um determinado nó ficam à esquerda, e números maiores do que o nó selecionado devem ficar à direita. Dessa forma, caso um usuário necessite procurar um número, o programa não necessitará percorrer todos os caminhos possíveis, bastando apenas verificar se o número solicitado é maior ou menor do que aquele nó.

</div>

<br>

## <h2 align = "center"> Exercício Nº 3: ⚖ BST com Balanceamento </h2> <br>

<div align = "center">

<img src = ".\Atividade-3\arvore_bst.png" width = 400px alt = "Imagem de uma árvore binária de busca com operaç~eos de balanceamento. Ou seja, ela fica equilibrada entre os dois lados.">

Para resolver o problema de desequilíbrio entre os galhos da árvore binária, foi criada operações de rotação. Isso permite que caso um lado fique maior que o outro -- prejudicando a eficiência das operações de buscas -- seja rotacionado o eixo a fim de equilibrar os nós. O balanceamento garante que ao percorrer a árvore, no pior caso, ela não se torne uma lista, porque a tornaria ineficiente e demorada.

</div>

<br>

## <h2 align = "center"> Exercício Nº 4: 🌲 Árvore AVL </h2> <br>

<div align = "center">

<img src = ".\Atividade-4\arvore_avlRandon.png" width = 700px alt = "Imagem mostrando uma árvore AVL, a qual todos os filhos da raiz têm a mesma altura sempre que possível">

O Exercício Nº4 retrata a árvore AVL, uma árvore autobalanceada. A sua prinicpal atribuição é manter a árvore balanceada após operações de inserção e de remoção. Ela utiliza o *fator de balanceamento*  a fim de controlar as rotações, garantindo a complexidade O(log n).
</div>

<br>

## <h2 align = "center"> Exercício Nº 5: ⚡ Treino da AVL </h2> <br>

<div align = "center">

<img src = ".\imgs\atividade-5.png" height = 500px alt = "Imagem dos testes feitos com a AVL">

Por fim, o último exercício foi criado para a realização de testes com a AVL, com o objetivo de praticar os conceitos de desenvolvimento e concepção dessa estrutura. O treinamento envolveu criar cada componente do zero sob a orientação do professor, por isso não foi criado um diagrama para essa última árvore.
</div>

<br>

## ✨ Autor

<img src = "https://avatars.githubusercontent.com/u/187053289?v=4" width = 120px> <br>
<strong> Victor </strong>

## 📞 Contatos

<a href = "https://www.linkedin.com/in/victor-m-rodrigues/"><img alt="Static Badge" src="https://img.shields.io/badge/LinkedIn-0?style=for-the-badge&logoColor=%23FFFFFF&color=%230077B5&link=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fvictor-m-rodrigues%2F"></a> 
<a href = "https://github.com/Victor-M-S-Rodrigues07/"><img alt="Static Badge" src="https://img.shields.io/badge/GitHub-0?style=for-the-badge&logo=github&logoColor=%23ffffff&labelColor=%23000000&color=%2300000000"></a>
<a href = "https://cursos.alura.com.br/user/victorvicmr"><img alt="Static Badge" src="https://img.shields.io/badge/Alura-0?style=for-the-badge&color=%23100D36"></a>

🇧🇷 - 2025
