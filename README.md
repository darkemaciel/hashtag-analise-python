# Análise de Cancelamentos de Clientes

## Descrição

Projeto de análise de dados em Python que investiga os principais motivos de cancelamento de clientes em uma base de mais de 800 mil clientes. O objetivo é identificar padrões de cancelamento e propor ações eficientes para reduzir esse número.

## Estrutura do Projeto

```
.
├── analise.ipynb           # Notebook com toda a análise exploratória
├── cancelamentos.csv       # Base de dados com informações dos clientes
├── requirements.txt        # Dependências do projeto
├── .gitignore             # Arquivos ignorados pelo Git
└── README.md              # Este arquivo
```

## Análise Realizada

O projeto identifica os seguintes fatores críticos de cancelamento:

1. **Contrato Mensal**: Clientes com contrato mensal apresentam 100% de cancelamento
   - Ação: Oferecer descontos nos planos anuais e trimestrais

2. **Ligações para Call Center**: Clientes que ligam mais de 4 vezes cancelam
   - Ação: Criar processo para resolver problemas em no máximo 3 ligações

3. **Atraso de Pagamento**: Clientes com mais de 20 dias de atraso cancelam
   - Ação: Política de resolver atrasos em até 10 dias

4. **Gasto Total**: Clientes que gastam menos de 500 reais cancelam
   - Ação: Oferecer descontos para clientes com menor gasto

## Instalação

### Pré-requisitos
- Python 3.8+
- pip

### Passos

1. Clone o repositório:
```bash
git clone git@github.com:darkemaciel/hashtag-analise-python.git
cd hashtag-analise-python
```

2. Crie um ambiente virtual:
```bash
python -m venv venv
source venv/Scripts/activate  # Windows
# ou
source venv/bin/activate      # Linux/Mac
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

## Uso

Abra o Jupyter Notebook com a análise completa:

```bash
jupyter notebook analise.ipynb
```

## Dependências Principais

- **pandas**: Manipulação e análise de dados
- **plotly**: Criação de gráficos interativos
- **numpy**: Computação numérica
- **ipython**: Shell interativo Python

Para a lista completa, consulte `requirements.txt`.

## Arquivos Ignorados

Este projeto ignora:
- `/venv/` - Ambiente virtual
- `*.pdf` - Arquivos PDF

## Autor

Projeto realizado como parte do curso "Python Insights - Analisando Dados com Python" da Hashtag Treinamentos.

---

**Última atualização**: 2026-07-10
