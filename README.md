#Sistema de Protocolos da Prefeitura

O Sistema de Protocolos da Prefeitura é uma solução desenvolvida para gerenciar, automatizar e otimizar o processo de protocolamento de documentos em uma prefeitura. O sistema permite que munícipes protocolizem documentos, que são automaticamente direcionados para as secretarias responsáveis, com prazos e regras claras para respostas. Além disso, oferece ferramentas de administração para gestão de secretarias, funcionários e relatórios de produtividade.

Funcionalidades Principais
Protocolamento de Documentos:

Munícipes podem protocolar qualquer tipo de documento.

Triagem automática usando IA para direcionar o documento à secretaria correta.

Gestão de Secretarias:

Administradores podem adicionar, editar ou remover secretarias e funcionários.

Prazos de 48 horas para respostas, com bloqueio automático em caso de atraso.

Relatórios de Produtividade:

O prefeito tem acesso a relatórios detalhados sobre o desempenho das secretarias.

Interface Amigável:

Interface gráfica no estilo Windows, desenvolvida com tkinter, para facilitar o uso por munícipes e administradores.

Tecnologias Utilizadas
Backend:

Python (Flask) para a API RESTful.

SQLite para armazenamento de dados.

IA simples para triagem de documentos (NLTK ou spaCy).

Frontend:

tkinter para a interface gráfica.

Ferramentas:

Git para controle de versão.

SQLite para banco de dados.

Como Executar o Projeto
Pré-requisitos
Python 3.8 ou superior.

Pip (gerenciador de pacotes do Python).

Passos para Configuração
Clone o repositório:

bash
Copy
git clone https://github.com/AlfredAlpha/prefeitura_protocolos.git
cd prefeitura_protocolos
Instale as dependências:
Navegue até a pasta backend e instale as dependências:

bash
Copy
cd backend
pip install -r requirements.txt
Inicialize o banco de dados:
Execute o script de inicialização do banco de dados:

bash
Copy
python ../scripts/init_db.py
Execute o backend:
Inicie o servidor Flask:

bash
Copy
python app.py
Execute o frontend:
Em outro terminal, navegue até a pasta frontend e inicie a interface gráfica:

bash
Copy
cd ../frontend
python main.py
Estrutura do Projeto
Copy
prefeitura_protocolos/
├── backend/              # Código do servidor Flask
├── frontend/             # Interface gráfica com tkinter
├── database/             # Banco de dados e scripts SQL
├── tests/                # Testes automatizados
├── scripts/              # Scripts utilitários
├── logs/                 # Logs do sistema
├── README.md             # Documentação do projeto
└── .gitignore            # Arquivo para ignorar arquivos no Git
Como Contribuir
Contribuições são bem-vindas! Siga os passos abaixo:

Faça um fork do projeto.

Crie uma branch para sua feature:

bash
Copy
git checkout -b minha-feature
Commit suas mudanças:

bash
Copy
git commit -m "Adicionando nova funcionalidade"
Push para a branch:

bash
Copy
git push origin minha-feature
Abra um Pull Request.

Licença
Este projeto está licenciado sob a MIT License. Consulte o arquivo LICENSE para mais detalhes.


Nome: Alfredo Luís Amorim

E-mail: alfredoamorim@gmail.com

GitHub: AlfredAlpha
