# Nota_10

# 🐍 Caderno Temático — Estudos em Python

> Repositório dedicado ao aprendizado progressivo da linguagem Python, reunindo anotações, exemplos práticos e projetos desenvolvidos ao longo da jornada de estudo.

---

## 📌 Contexto e Objetivos

### Por que Python?

Python é uma das linguagens de programação mais utilizadas no mundo, reconhecida pela sua sintaxe simples e legível, versatilidade e pela enorme comunidade de desenvolvedores. Presente em áreas como desenvolvimento web, automação, ciência de dados, inteligência artificial e muito mais, Python se tornou uma escolha natural para quem deseja ingressar no universo da programação.

Este repositório nasceu da necessidade de organizar e documentar o processo de aprendizado da linguagem de forma estruturada, criando um material de consulta pessoal que evolui junto com o conhecimento adquirido.

### 🎯 Objetivos de Estudo

- **Compreender os fundamentos** da linguagem Python: variáveis, tipos de dados, estruturas de controle, funções e orientação a objetos
- **Explorar bibliotecas essenciais** do ecossistema Python, como `pandas`, `plotly`, `matplotlib`, `numpy` e outras
- **Desenvolver projetos práticos** que apliquem os conceitos estudados em situações reais
- **Construir uma base sólida** para avançar em áreas como análise de dados, automação e desenvolvimento de aplicações
- **Documentar o aprendizado** de forma clara, para revisão futura e compartilhamento com outros estudantes

---

## 📂 Estrutura do Repositório

```
📦 estudos-python/
├── 📁 fundamentos/
│   ├── variaveis_e_tipos.py
│   ├── estruturas_de_controle.py
│   ├── funcoes.py
│   └── orientacao_a_objetos.py
├── 📁 bibliotecas/
│   ├── pandas/
│   ├── plotly/
│   └── numpy/
├── 📁 projetos/
│   └── ...
└── README.md
```

---

## 📚 Conteúdos Abordados

| Módulo | Tópicos | Status |
|---|---|---|
| Fundamentos | Variáveis, tipos, operadores | ✅ Concluído |
| Estruturas de Controle | `if`, `for`, `while` | ✅ Concluído |
| Funções | Definição, parâmetros, retorno | 🔄 Em andamento |
| Bibliotecas | pandas, plotly, numpy | 🔄 Em andamento |
| Projetos Práticos | Análise de dados, automação | 🔜 Em breve |

---

## 🛠️ Tecnologias e Ferramentas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

---

## ▶️ Como Executar os Exemplos

**1. Clone o repositório:**
```bash
git clone https://github.com/seu-usuario/estudos-python.git
cd estudos-python
```

**2. Crie e ative o ambiente virtual:**
```bash
python -m venv .venv

# Windows
.venv\Scripts\activate

# Mac/Linux
source .venv/bin/activate
```

**3. Instale as dependências:**
```bash
pip install pandas plotly numpy
```

**4. Execute qualquer arquivo:**
```bash
python fundamentos/variaveis_e_tipos.py
```

---

## 📈 Progresso

- [x] Configuração do ambiente de desenvolvimento
- [x] Fundamentos da linguagem
- [ ] Bibliotecas para análise de dados
- [ ] Projetos práticos
- [ ] Tópicos avançados

---

## 📝 Licença

Este repositório é de uso pessoal e educacional, livre para consulta e inspiração.

---

<p align="center">
  Feito com 💙 e muito <code>print("Hello, World!")</code>
</p>


O que é Python?
Conceito
Python é uma linguagem de programação de alto nível, criada por Guido van Rossum em 1991. É conhecida por sua sintaxe simples e legível, próxima do inglês, o que a torna ideal para iniciantes. Pode ser usada para análise de dados, automação, desenvolvimento web, inteligência artificial e muito mais.

Variáveis
Básico
Armazenam valores na memória. Em Python, não é preciso declarar o tipo — ele é inferido automaticamente.

nome = "Ana"
idade = 25
altura = 1.68
ativo = True
Tipos de dados
Básico
str — texto: "olá"
int — inteiro: 42
float — decimal: 3.14
bool — verdadeiro/falso: True
list — lista: [1, 2, 3]
dict — dicionário: {"a": 1}
Estruturas de controle
Fluxo
Controlam quais blocos de código são executados e quantas vezes.

# Condicional
if idade >= 18:
    print("maior de idade")
else:
    print("menor de idade")

# Laço for
for i in range(5):
    print(i)

# Laço while
contador = 0
while contador < 3:
    print(contador)
    contador += 1
Funções e estruturas
Funções
Reutilização
Blocos de código nomeados que realizam uma tarefa específica e podem ser chamados várias vezes.

def saudacao(nome):
    return f"Olá, {nome}!"

resultado = saudacao("Maria")
print(resultado)  # Olá, Maria!
Listas
Coleção
Coleção ordenada e mutável de itens.

frutas = ["maçã", "uva"]
frutas.append("pera")
print(frutas[0])  # maçã
Dicionários
Coleção
Coleção de pares chave-valor.

pessoa = {
  "nome": "João",
  "idade": 30
}
print(pessoa["nome"])
Bibliotecas usadas
pandas + plotly.express
Bibliotecas
Dupla essencial para análise e visualização de dados em Python.

pandas — organiza dados em tabelas chamadas DataFrames, permite filtrar, calcular e transformar dados com facilidade.
plotly.express — gera gráficos interativos (linha, barra, pizza, dispersão) a partir de DataFrames do pandas.
import pandas as pd
import plotly.express as px

df = pd.DataFrame({"mês": ["Jan","Fev"], "vendas": [100, 150]})
fig = px.bar(df, x="mês", y="vendas", title="Vendas")
fig.show()
