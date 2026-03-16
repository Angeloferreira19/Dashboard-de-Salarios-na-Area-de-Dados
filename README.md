# Dashboard de Salários na Área de Dados

Dashboard interativo construído com **Streamlit** e **Plotly** para análise de salários na área de dados. Permite explorar dados salariais de diferentes anos, senioridades, tipos de contrato e tamanhos de empresa.

## 🚀 Funcionalidades

- **Filtros Interativos**: Ano, Senioridade, Tipo de Contrato, Tamanho da Empresa
- **KPIs**: Salário médio, Salário máximo, Total de registros, Cargo mais frequente
- **Visualizações**:
  - Top 10 cargos por salário médio (gráfico de barras)
  - Distribuição de salários anuais (histograma)
  - Proporção de tipos de trabalho (gráfico de pizza)
  - Salário médio de Cientista de Dados por país (mapa coroplético)
- **Tabela de Dados**: Visualização detalhada dos dados filtrados

## 📋 Pré-requisitos

- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)

## 🔧 Instalação

1. **Clone o repositório** (ou baixe os arquivos):
   ```bash
   git clone <url-do-repositorio>
   cd imersao-dados-python
   ```

2. **Crie um ambiente virtual** (recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   # ou
   venv\Scripts\activate  # Windows
   ```

3. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Como Executar

Após a instalação, execute o comando:

```bash
streamlit run app.py
```

O dashboard será aberto automaticamente no seu navegador padrão em `http://localhost:8501`.

## 📁 Estrutura do Projeto

```
imersao-dados-python/
├── app.py              # Código principal do dashboard
├── requirements.txt    # Dependências do projeto
└── README.md           # Este arquivo
```

## 📦 Dependências

- `pandas==2.2.3`
- `streamlit==1.44.1`
- `plotly==5.24.1`

## 📄 Licença

Este projeto é para fins educacionais.

---

Desenvolvido com ❤️ durante a Imersão Dados Python Alura.