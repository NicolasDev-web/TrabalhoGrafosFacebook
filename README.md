# TrabalhoGrafosFacebook
# 🌐 Análise Estrutural e Comportamento de Escala Livre: Facebook Ego Networks

**Disciplina:** Resolução de Problemas em Grafos (Ciência da Computação)  
**Dataset:** [Facebook Ego Networks (SNAP)](https://snap.stanford.edu/data/ego-Facebook.html)  
**Categoria:** Redes Sociais  
**Equipe**:
Nicolas dos Santos Xavier | 2320299
Marcelo de Magalhães Rodrigues Filho | 2416511
João Pedro Mendes | 2417151

---

## 📋 Sobre o Projeto
Este repositório contém a análise topológica de uma rede social real (Facebook) utilizando a teoria dos grafos. O objetivo principal deste trabalho é extrair métricas estruturais fundamentais e investigar rigorosamente a hipótese de comportamento de **Escala Livre** (*Scale-Free*) através do ajuste da distribuição de graus por **Lei de Potência**, utilizando o método de Estimativa de Máxima Verossimilhança (MLE).

O projeto também inclui uma discussão crítica comparando o domínio de redes sociais (virtuais) com redes de infraestrutura física (estradas).

## 🛠️ Tecnologias e Dependências
O projeto foi desenvolvido em formato Jupyter Notebook (ideal para execução no Google Colab). As bibliotecas matemáticas e visuais utilizadas são:

* `networkx` (Modelação e métricas de grafos)
* `numpy` e `matplotlib` (Manipulação de arrays e visualização estática)
* `powerlaw` (Ajuste estatístico de distribuições de cauda pesada / MLE)
* `manim` e `IPython.display` (Animações de alta fidelidade para apresentação)

## 🚀 Como Executar o Projeto (Guia Rápido)

### Como Executa: Execução no Google Colab (Recomendado)
A forma mais rápida de reproduzir os resultados sem configurar o ambiente localmente é através do Google Colab:
1. Faça o download do ficheiro compactado do dataset (`facebook.tar.gz`) diretamente do [site do SNAP](https://snap.stanford.edu/data/ego-Facebook.html).
2. Abra o ficheiro `.ipynb` deste repositório no Google Colab.
3. No menu lateral esquerdo do Colab (ícone de pasta), faça o upload do ficheiro `facebook.tar.gz` para a diretoria raiz.
4. Execute as células sequencialmente (`Shift + Enter`).
   * *Nota:* O notebook já contém os comandos `!pip install powerlaw` e `!pip install manim` para instalar as dependências automaticamente no ambiente da nuvem.
