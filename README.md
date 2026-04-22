# Python
## 🎯 Sobre o Projeto

Este projeto apresenta uma análise completa de dados salariais de profissionais da área de dados, permitindo explorar tendências, comparar cargos e entender a distribuição de salários ao redor do mundo. A aplicação oferece visualizações interativas e filtros dinâmicos para análises personalizadas.

## ✨ Funcionalidades

### 📈 Métricas Principais
- **Salário Médio**: Média salarial anual em USD dos dados filtrados
- **Salário Máximo**: Maior salário registrado no dataset
- **Total de Registros**: Quantidade de profissionais analisados
- **Cargo Mais Frequente**: Cargo com maior número de registros

### 🔍 Filtros Interativos
- **Ano**: Filtre dados de 2020 a 2025
- **Senioridade**: Júnior, Pleno, Sênior e Executivo
- **Tipo de Contrato**: Integral, Freelancer, Parcial e Seis
- **Tamanho da Empresa**: Pequena, Média e Grande

### 📊 Visualizações

#### 1. Top 10 Cargos por Salário Médio
Gráfico de barras horizontal mostrando os 10 cargos mais bem remunerados.

#### 2. Distribuição de Salários Anuais
Histograma apresentando a distribuição de faixas salariais no dataset.

#### 3. Proporção dos Tipos de Trabalho
Gráfico de pizza (donut chart) exibindo a distribuição entre trabalho presencial, remoto e híbrido.

#### 4. Salário Médio de Cientista de Dados por País
Mapa coroplético mundial mostrando a média salarial de Data Scientists por país (código ISO3).

### 📋 Tabela de Dados Detalhados
Visualização completa dos dados filtrados com todas as colunas disponíveis.

## 🗂️ Estrutura dos Dados

O dataset contém **133.339 registros** com as seguintes colunas:

| Coluna | Descrição |
|--------|-----------|
| `ano` | Ano de referência (2020-2025) |
| `senioridade` | Nível de senioridade do profissional |
| `contrato` | Tipo de contratação |
| `cargo` | Título do cargo |
| `salario` | Salário na moeda original |
| `moeda` | Moeda original do salário |
| `usd` | Salário convertido para USD |
| `residencia` | País de residência |
| `remoto` | Modalidade de trabalho (presencial/remoto/híbrido) |
| `empresa` | País da empresa |
| `tamanho_empresa` | Porte da empresa |
| `residencia_iso3` | Código ISO3 do país de residência |

## 🚀 Como Executar

### Pré-requisitos
- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/caiosantiagotr/Analise-de-Dados.git
cd Analise-de-Dados

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Execute a aplicação:
```bash
streamlit run app.py
```

4. Acesse no navegador:
```
https://dadosan.streamlit.app/
```

## 📦 Dependências

```
pandas==2.2.3
streamlit==1.44.1
plotly==5.24.1
```

## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem principal do projeto
- **Streamlit**: Framework para criação da aplicação web
- **Pandas**: Manipulação e análise de dados
- **Plotly Express**: Criação de gráficos interativos

## 📸 Screenshots

### Aplicação Principal
Visualização das métricas gerais e filtros laterais.

### Gráficos Interativos
Análises visuais dos top cargos, distribuição salarial e modalidades de trabalho.

### Mapa Mundial
Distribuição geográfica dos salários de Cientistas de Dados.

## 🎓 Aprendizados

Durante o desenvolvimento deste projeto na Imersão Dados Python da Alura, foram explorados:

- Análise exploratória de dados (EDA)
- Criação de aplicações interativas com Streamlit
- Visualização de dados com Plotly
- Manipulação de dados com Pandas
- Filtros dinâmicos e interatividade
- Boas práticas em layout e UX de aplicações web

## 📈 Insights Principais

- Cargos de liderança e especialização técnica avançada apresentam as maiores médias salariais
- A modalidade de trabalho remoto representa a maior parcela dos registros
- Existe grande variação salarial entre diferentes países e regiões
- A senioridade é um fator determinante na remuneração

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um Fork do projeto
2. Criar uma Branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a Branch (`git push origin feature/NovaFuncionalidade`)
5. Abrir um Pull Request

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais durante a Imersão Dados Python da Alura 2025.

## 👤 Autor

Desenvolvido durante a **Imersão Dados Python - Alura 2026**

## 🙏 Agradecimentos

- [Alura](https://www.alura.com.br/) pela imersão e conteúdo educacional
- Comunidade Python pela excelência das bibliotecas utilizadas
- Todos os participantes da imersão pelo compartilhamento de conhecimento

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!