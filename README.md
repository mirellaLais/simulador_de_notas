# 🎓 Simulador de Sistema Acadêmico de Notas

## 📌 Sobre o Projeto

O **Simulador de Sistema Acadêmico de Notas** é um projeto desenvolvido para simular, analisar e validar dados acadêmicos de estudantes, utilizando conceitos de estatística, análise de dados, inferência estatística e simulação computacional.

O projeto permite gerar dados sintéticos de notas de alunos e realizar análises para compreender o comportamento do desempenho acadêmico ao longo dos semestres, identificar padrões e avaliar a consistência dos resultados obtidos.

A solução contempla análises desenvolvidas em Python e uma aplicação web para visualização dos dados e resultados.

## 🎯 Objetivos

* Simular um sistema acadêmico de notas com dados sintéticos.
* Analisar o desempenho dos estudantes por meio de métodos estatísticos.
* Avaliar a distribuição das notas e suas variações.
* Investigar tendências de desempenho ao longo dos semestres.
* Aplicar técnicas de inferência estatística e simulação de Monte Carlo.
* Validar os resultados por meio de testes e análises de sensibilidade.
* Apresentar os resultados de forma visual e organizada.

## 📊 Escopo da Simulação

O sistema considera a seguinte estrutura acadêmica:

| Característica     | Quantidade |
| ------------------ | ---------: |
| Turmas             |          6 |
| Alunos por turma   |         30 |
| Total de alunos    |        180 |
| Disciplinas        |         10 |
| Semestres          |          8 |
| Registros de notas |     14.400 |

Os dados utilizados são sintéticos, ou seja, são gerados artificialmente para permitir a realização das análises sem depender de informações reais de estudantes.

## ⚙️ Funcionamento

A simulação utiliza um modelo aditivo para representar as notas dos estudantes. Nesse modelo, o resultado pode ser influenciado por diferentes fatores, como:

* Nota ou desempenho de referência.
* Disciplina e professor.
* Turno de estudo.
* Idade dos estudantes.
* Semestre cursado.
* Características individuais dos alunos.
* Variações aleatórias.

A partir desses fatores, o sistema gera dados que podem ser utilizados em análises estatísticas e na identificação de padrões de desempenho acadêmico.

## 🧪 Análises Realizadas

O projeto contempla diferentes tipos de análise:

### 1. Estatística descritiva

Utilizada para resumir e compreender os dados, considerando medidas como média, mediana, desvio padrão, valores mínimos e máximos.

### 2. Análise de distribuições

Permite observar a distribuição das notas e identificar padrões, dispersões e possíveis comportamentos atípicos.

### 3. Análise temporal

Investiga a evolução do desempenho acadêmico ao longo dos semestres, permitindo observar tendências e variações.

### 4. Inferência estatística

Utiliza métodos estatísticos para estimar parâmetros e avaliar hipóteses relacionadas aos dados simulados.

### 5. Simulação de Monte Carlo

Permite repetir experimentos computacionais para avaliar a variabilidade dos resultados e verificar o comportamento do modelo sob diferentes condições.

### 6. Análise de sensibilidade

Avalia como alterações nos parâmetros da simulação influenciam os resultados, contribuindo para compreender a estabilidade do modelo.

### 7. Modelagem e agrupamento

O projeto também contempla técnicas de regressão e agrupamento, como K-Means, para explorar relações entre variáveis e identificar grupos com características semelhantes.

## 🛠️ Tecnologias Utilizadas

### Python e análise de dados

* **Python:** linguagem utilizada no desenvolvimento das análises e simulações.
* **NumPy:** operações numéricas e cálculos matemáticos.
* **Pandas:** manipulação e organização dos dados.
* **SciPy:** métodos científicos e estatísticos.
* **Matplotlib:** criação de gráficos.
* **Seaborn:** visualização e exploração estatística dos dados.

### Aplicação Web

* **TypeScript:** desenvolvimento da lógica da aplicação.
* **Vite:** ferramenta de desenvolvimento e execução da aplicação web.
* **Chart.js:** criação de gráficos e visualizações.
* **SQLite:** estrutura de banco de dados.
* **sql.js:** utilização do SQLite em ambiente JavaScript/WebAssembly.
* **IndexedDB:** armazenamento de dados no navegador.

## 🚀 Como Executar

### Executando o notebook Python

O notebook pode ser executado no Google Colab ou em um ambiente Python compatível.

**1.** Abra o arquivo `Simulador_Notas_Colab.ipynb` no Google Colab.

**2.** Instale as dependências necessárias, caso ainda não estejam disponíveis:

```bash
pip install numpy pandas scipy matplotlib seaborn openpyxl
```

**3.** Execute as células do notebook em ordem.

**4.** Observe os resultados gerados, incluindo tabelas, gráficos e testes estatísticos.

**Observação:** os nomes dos arquivos e os comandos devem ser ajustados conforme a estrutura real do repositório.

### Executando a aplicação web

Para executar a aplicação web, é necessário ter o Node.js e o gerenciador de pacotes utilizado pelo projeto instalados.

Na pasta da aplicação, execute:

```bash
npm install
```

Em seguida, inicie o servidor de desenvolvimento:

```bash
npm run dev
```

O Vite apresentará no terminal o endereço local para acessar a aplicação pelo navegador.

**Importante:** os comandos dependem dos scripts definidos no arquivo `package.json` do projeto.

## ✅ Validação dos Resultados

A validação é uma etapa importante para verificar se o comportamento observado na simulação está de acordo com as propriedades esperadas do modelo.

O projeto utiliza estratégias como:

* Comparação entre resultados simulados e valores teóricos.
* Verificação de propriedades estatísticas.
* Avaliação de intervalos de confiança.
* Análise de resultados de testes de hipóteses.
* Repetição de experimentos com diferentes parâmetros.
* Análise de sensibilidade para avaliar a estabilidade dos resultados.

Os resultados devem ser interpretados de acordo com as configurações utilizadas em cada experimento. A aprovação de um teste deve ser confirmada pela execução efetiva do código e pela verificação das mensagens ou resultados apresentados.

## 📈 Resultados Esperados

Com a execução do projeto, espera-se obter:

* Dados acadêmicos sintéticos organizados.
* Estatísticas descritivas sobre as notas.
* Gráficos para facilitar a interpretação dos dados.
* Análises do desempenho ao longo dos semestres.
* Resultados de testes estatísticos e inferência.
* Avaliação da estabilidade do modelo.
* Visualizações que facilitem a compreensão dos resultados.

Os resultados numéricos dependem dos parâmetros, das sementes aleatórias e das configurações utilizadas durante a execução.

## ⚠️ Limitações

* Os dados são sintéticos e não representam necessariamente o desempenho de estudantes reais.
* Os resultados dependem das hipóteses e dos parâmetros definidos no modelo.
* As conclusões estatísticas devem considerar as características da simulação.
* A aplicação não deve ser utilizada isoladamente para tomar decisões acadêmicas reais.
* Os resultados de validação precisam ser conferidos por meio da execução dos testes correspondentes.

## 🔮 Melhorias Futuras

Algumas possibilidades de evolução do projeto são:

* Implementar novos modelos estatísticos.
* Ampliar a quantidade de variáveis acadêmicas.
* Melhorar a interface e a experiência do usuário.
* Adicionar filtros por turma, disciplina e semestre.
* Desenvolver novas visualizações interativas.
* Automatizar a execução dos testes de validação.
* Melhorar a documentação técnica e os procedimentos de instalação.

## 📁 Estrutura do Projeto

A estrutura abaixo é ilustrativa e deve ser ajustada para refletir os diretórios e arquivos existentes no repositório.

```text
simulador-academico-notas/
│
├── README.md
│
├── Simulador_Notas_Colab.ipynb
│
├── python/
│   └── validacao_sensibilidade.py
│
├── src/
│   ├── stats.ts
│   └── ...
│
├── package.json
├── index.html
└── vite.config.ts
```

## 📚 Considerações Finais

O Simulador de Sistema Acadêmico de Notas reúne conceitos de programação, estatística e análise de dados para investigar o comportamento de um modelo acadêmico simulado.

A combinação entre Python, métodos estatísticos e visualizações em uma aplicação web permite explorar os dados de diferentes maneiras, facilitando a interpretação dos resultados e a avaliação do modelo.

O projeto também contribui para o aprendizado de análise de dados, validação computacional e desenvolvimento de aplicações.

---

**Projeto acadêmico — Simulador de Sistema Acadêmico de Notas.**

