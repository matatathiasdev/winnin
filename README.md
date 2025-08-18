O projeto 🚀

Um projeto experimental criado como parte de um teste técnico em Engenharia de Dados. Ele demonstra meu processo de extração, transformação e análise de dados, integrando múltiplas fontes públicas como Wikipedia e YouTube.

🔹 Motivação

Aplicar conceitos de Engenharia de Dados de forma prática e organizada.

🔹 Funcionalidades

Integração com Wikipedia: Enriquecimento de dados de criadores do YouTube.

Criação de tabelas estruturadas: Transformação de dados brutos em formatos prontos para análise.

Análise exploratória: Descoberta de padrões e insights sobre os criadores de conteúdo.

Pipeline completo: Do scraping à análise final, com notebooks claros e documentados.

🔹 Estrutura do Projeto
```
winnin/
│
├─ notebooks/          # Notebooks Jupyter
│   ├─ create_table_user_yt_from_wikipedia_api.ipynb
│   ├─ create_table_creators_scrape_wiki.ipynb
│   ├─ create_table_posts_creator.ipynb
│   └─ analyze_creators.ipynb
├─ data/               # Arquivos CSV/JSON usados nos testes
├─ README.md           # Este arquivo
└─ requirements.txt    # Dependências Python
```
🔹 Como Rodar

Clone o repositório:

git clone https://github.com/matatathiasdev/winnin.git

Criar uma conta no Databricks na versão Free

Abra os notebooks na seguinte ordem:

create_table_user_yt_from_wikipedia_api.ipynb

create_table_creators_scrape_wiki.ipynb

create_table_posts_creator.ipynb

analyze_creators.ipynb

Cada notebook contém instruções detalhadas e exemplos de execução.

🔹 Aprendizado e Desafios

Estruturar dados de múltiplas fontes mantendo consistência.

Criar pipelines reproduzíveis e fáceis de manter.

Aplicar boas práticas de Python, Pandas e requests em um projeto completo.

Transformar dados brutos em insights relevantes de forma clara e organizada.

🔹 Contato

Matheus Rodrigues – GitHub
