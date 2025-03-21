## Scraping da B3 - Composição do Índice IBOVESPA

Este projeto realiza o web scraping da composição do índice IBOVESPA diretamente do site da B3, salvando os dados localmente em formato Parquet para análise posterior.
### 📌 Funcionalidades

- Acessa a página da B3 e extrai os dados da composição do índice IBOVESPA.

- Percorre todas as páginas do índice para capturar os dados completos.

- Salva as informações coletadas em um arquivo Parquet com a data do pregão.

### 🛠️ Tecnologias Utilizadas

- Python

- Selenium para automação do navegador

- BeautifulSoup para parsing do HTML

- Pandas para manipulação e exportação dos dados

### 🚀 Como Executar o Projeto

**1️⃣ Clonar o Repositório**

git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

**2️⃣ Criar um Ambiente Virtual (Opcional, mas Recomendado)**

python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate    # Windows

**3️⃣ Instalar as Dependências**

pip install -r requirements.txt

**4️⃣ Executar o Script**

python scraping_b3_tipado.py

### 📂 Estrutura de Arquivos

📁 seu-repositorio

│-- scraping_b3_tipado.py  # Script principal

│- README.md              # Documentação

│-- data_pregao=YYYY-MM-DD/ # Diretório com arquivos Parquet gerados

### 📢 Observações

O script utiliza o Google Chrome e o Chromedriver. Certifique-se de que ambos estão instalados e compatíveis.

Se necessário, atualize o caminho do chromedriver no código.

### 📄 Licença

Este projeto é de código aberto e está licenciado sob a MIT License. Sinta-se à vontade para contribuir! 🎯
