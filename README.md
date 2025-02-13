# prefeitura_protocolos

Aqui está um exemplo de `README.md` bem detalhado e profissional para o seu projeto de **Sistema de Protocolos da Prefeitura**. Ele cobre desde a descrição do projeto até instruções de instalação, uso e contribuição.

---

# Sistema de Protocolos da Prefeitura

O **Sistema de Protocolos da Prefeitura** é uma solução desenvolvida para gerenciar, automatizar e otimizar o processo de protocolamento de documentos em uma prefeitura. O sistema permite que munícipes protocolizem documentos, que são automaticamente direcionados para as secretarias responsáveis, com prazos e regras claras para respostas. Além disso, oferece ferramentas de administração para gestão de secretarias, funcionários e relatórios de produtividade.

---

## Funcionalidades Principais

- **Protocolamento de Documentos**:
  - Munícipes podem protocolar qualquer tipo de documento.
  - Triagem automática usando IA para direcionar o documento à secretaria correta.
  
- **Gestão de Secretarias**:
  - Administradores podem adicionar, editar ou remover secretarias e funcionários.
  - Prazos de 48 horas para respostas, com bloqueio automático em caso de atraso.

- **Relatórios de Produtividade**:
  - O prefeito tem acesso a relatórios detalhados sobre o desempenho das secretarias.

- **Interface Amigável**:
  - Interface gráfica no estilo Windows, desenvolvida com `tkinter`, para facilitar o uso por munícipes e administradores.

---

## Tecnologias Utilizadas

- **Backend**:
  - Python (Flask) para a API RESTful.
  - SQLite para armazenamento de dados.
  - IA simples para triagem de documentos (NLTK ou spaCy).

- **Frontend**:
  - `tkinter` para a interface gráfica.

- **Ferramentas**:
  - Git para controle de versão.
  - SQLite para banco de dados.

---

## Como Executar o Projeto

### Pré-requisitos

- Python 3.8 ou superior.
- Pip (gerenciador de pacotes do Python).

### Passos para Configuração

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/AlfredAlpha/prefeitura_protocolos.git
   cd prefeitura_protocolos
   ```

2. **Instale as dependências**:
   Navegue até a pasta `backend` e instale as dependências:
   ```bash
   cd backend
   pip install -r requirements.txt
   ```

3. **Inicialize o banco de dados**:
   Execute o script de inicialização do banco de dados:
   ```bash
   python ../scripts/init_db.py
   ```

4. **Execute o backend**:
   Inicie o servidor Flask:
   ```bash
   python app.py
   ```

5. **Execute o frontend**:
   Em outro terminal, navegue até a pasta `frontend` e inicie a interface gráfica:
   ```bash
   cd ../frontend
   python main.py
   ```

---

## Estrutura do Projeto

```
prefeitura_protocolos/
├── backend/              # Código do servidor Flask
├── frontend/             # Interface gráfica com tkinter
├── database/             # Banco de dados e scripts SQL
├── tests/                # Testes automatizados
├── scripts/              # Scripts utilitários
├── logs/                 # Logs do sistema
├── README.md             # Documentação do projeto
└── .gitignore            # Arquivo para ignorar arquivos no Git
```

---

## Como Contribuir

Contribuições são bem-vindas! Siga os passos abaixo:

1. Faça um fork do projeto.
2. Crie uma branch para sua feature:
   ```bash
   git checkout -b minha-feature
   ```
3. Commit suas mudanças:
   ```bash
   git commit -m "Adicionando nova funcionalidade"
   ```
4. Push para a branch:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

---

## Licença

Este projeto está licenciado sob a **MIT License**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## Contato

- **Desenvolvedor**: Alfredo Luis Amorim
- **Email**: alfredoamorim@gmail.com
- **GitHub**: https://github.com/seu-usuario](https://github.com/seu-usuario)

---

Este `README.md` é abrangente e cobre todos os aspectos essenciais do projeto. Você pode personalizá-lo conforme necessário, adicionando detalhes específicos do seu projeto ou da sua equipe. 😊
