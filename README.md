# Introdução à Ciência de Dados e IA Preditiva (Python)

Material de apoio do minicurso da **X Semana do PIEPEX** — Instituto de Ciências Sociais Aplicadas (ICSA).
O repositório reúne os **slides da apresentação** e o **notebook** com todos os exemplos práticos executados em aula.

[![Aberto no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DqovdPxV4e5tM81tAsDeJLlroGjlnN9A)

> O botão acima abre o notebook da aula no Google Colab. Para editar e executar, use **Arquivo → Salvar uma cópia no Drive**.

---

## Sobre o minicurso

- **Evento:** X Semana do PIEPEX · ICSA
- **Data / horário:** 22/09/2026 · 20h50–22h30
- **Local:** D-201 (laboratório)
- **Nível:** introdutório — sem pré-requisitos
- **Ministrante:** Alice Duarte — Atuária (UNIFAL) · Mestre em Estatística (UFLA) · Atuária na Mirador

A proposta é prática: entender o raciocínio da Ciência de Dados e executar tudo junto, ao vivo, no Google Colab.

---

## Conteúdo do repositório

| Arquivo | O que é |
|---|---|
| `minicurso-ciencia-de-dados.html` | Apresentação (slides). Abre direto no navegador. |
| `minicurso_ciencia_de_dados.ipynb` | Notebook com os exemplos em Python. |

---

## Como usar

### Apresentação (slides)
Baixe o arquivo `minicurso-ciencia-de-dados.html` e abra com dois cliques em qualquer navegador — não precisa instalar nada. Para projetar, aperte **F11** (tela cheia). Navegue com as setas `←` `→`, pelos botões na base ou deslizando no celular.

### Notebook (recomendado: Google Colab)
Escolha uma das opções:

1. **Botão "Aberto no Colab"** no topo deste README (abre o notebook da aula).
2. **Upload manual:** acesse [colab.research.google.com](https://colab.research.google.com/) → **Arquivo → Fazer upload de notebook** → selecione o `.ipynb`.
3. **Localmente**, com Python instalado:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   jupyter notebook
   ```

No Colab, todas as bibliotecas já vêm instaladas — é só executar as células (**Ambiente de execução → Executar tudo**).

---

## O que o curso aborda

- O que é Ciência de Dados e a jornada dos dados (da coleta ao risco futuro)
- Análise Exploratória (EDA) com uma base real
- Modelos determinísticos × estocásticos e o papel de cada um
- Simulação de Monte Carlo e cenários (pessimista / base / otimista)
- IA Preditiva e modelos de Machine Learning (regressão, árvores, boosting, KNN/SVM, redes neurais)
- Um modelo preditivo do início ao fim, com avaliação e interpretação

---

## Base de dados

Os exemplos usam o **Medical Cost Personal Dataset** (`insurance.csv`): 1.338 registros e 7 colunas
(`age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`), sem valores faltantes.
São **dados simulados** a partir de padrões demográficos dos EUA — realistas e livres de questões de privacidade,
ideais para ensino. Os valores de `charges` estão em dólares (US$).

O notebook carrega a base automaticamente a partir desta URL:

```
https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/insurance.csv
```

---

## Licença

Material educacional de uso livre para fins de estudo e ensino, com atribuição.
