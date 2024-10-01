# Previsão Temporal de Demanda de Vagas

Este projeto aplica o modelo ARIMA (AutoRegressive Integrated Moving Average) para prever a demanda futura de vagas no mercado de trabalho com base em dados históricos. O objetivo principal é identificar padrões sazonais e projetar tendências futuras, oferecendo insights úteis para profissionais de recrutamento e empresas que desejam se preparar para flutuações na demanda de vagas.

## 📊 Visão Geral

O modelo ARIMA foi utilizado para prever o número de vagas diárias, permitindo a identificação de períodos de alta e baixa demanda. Com isso, é possível observar o comportamento do mercado de trabalho e prever possíveis aumentos ou diminuições na oferta de vagas em datas futuras.

### 🔍 Funcionalidades

- Divisão dos dados em **treino** e **teste** para validação do modelo.
- Utilização do modelo ARIMA para previsões de séries temporais.
- Visualização gráfica que compara o período de treino, teste e previsão.
- Insights sobre os picos e a estabilidade da demanda de vagas.

## 📈 Tecnologias Utilizadas

- **Python**: Linguagem utilizada para desenvolvimento.
- **ARIMA**: Modelo para análise de séries temporais.
- **Pandas**: Manipulação e análise de dados.
- **Matplotlib**: Visualização gráfica dos resultados.

## 🔧 Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd nome-do-repositorio
   ```
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Como Executar

1. Certifique-se de que os dados de vagas estão disponíveis e no formato correto.
2. Execute o script principal para gerar a previsão:
   ```bash
   python main.py
   ```
3. O gráfico de previsão será gerado e salvo automaticamente.

## 📅 Conjunto de Dados

O dataset utilizado no projeto contém informações diárias sobre a quantidade de vagas postadas. Foi dividido da seguinte forma:

- **Treino**: Período inicial (80% dos dados).
- **Teste**: Período final (20% dos dados).
  
### 🎯 Objetivo

- Analisar o comportamento do mercado de trabalho ao longo do tempo.
- Fornecer uma previsão da demanda futura de vagas para ajudar empresas e profissionais de recursos humanos a tomar decisões estratégicas.

## 🔮 Resultados

Os resultados mostram uma volatilidade na demanda durante o período de teste, com um pico elevado de vagas a partir de meados de 2024. A previsão sugere uma estabilização nos meses seguintes, o que pode indicar um equilíbrio no mercado de trabalho após a alta instabilidade.

## 🛠️ Melhorias Futuras

- Testar outros modelos de séries temporais, como SARIMA ou Prophet, para melhorar a acurácia.
- Explorar variáveis externas que podem influenciar a demanda de vagas, como dados econômicos.
- Implementar uma interface gráfica para facilitar o uso e a visualização dos resultados.

## 📬 Contato

Para mais informações sobre o projeto, entre em contato comigo pelo LinkedIn:

- **LinkedIn**: [Meu perfil](https://www.linkedin.com/in/victor--viegas/)
Esse README apresenta uma visão clara do projeto e pode ser facilmente ajustado para se adequar às suas preferências ou detalhes específicos.
