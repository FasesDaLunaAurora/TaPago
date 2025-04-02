# 📌 TaPago

Uma plataforma para desenvolvedores e estudantes que querem tirar projetos do papel! Os usuários adicionam ideias de projetos e desafiam amigos a "comprá-las". 

Se o projeto não for entregue no prazo combinado, o criador precisa pagar ao amigo o valor estipulado. A ideia é incentivar o compromisso e a motivação para finalizar projetos.

Inicialmente concebido para ser uma aplicação web.

## 💡Definições e conceitos:

- **Ludus:** nome do app, remete ao nome das antigas escolas de treinamento de gladiadores
- **Arena:** grupo de amigos que verá os projetos e poderá apostar neles, remete a onde ocorriam combates de gladiadores
- **Leão:** projeto que será executado, alusão ao fato de ter que "matar" um leão para entregar o projeto
- **Patrono:** amigo que vai apostar no projeto, na antiguidade eram figuras ricas e influentes contra a procrastinação
- **Tributo:** preço que o Gladiador coloca em jogo ao aceitar um desafio, na Roma Antiga um tributo era um pagamento feito como forma de submissão ou para garantir proteção
  
## 🚀 Tecnologias Utilizadas

- **Linguagem:** Python 3.10+
- **Frameworks:** Flask (para backend), SQLite (banco de dados)
- **Outras Ferramentas:** Docker (para ambiente de execução opcional), pytest (para testes)

## 📂 Estrutura do Projeto

```bash
📁 devchallenge
   ├── 📁 src  # Código-fonte
   │   ├── app.py  # Ponto de entrada principal
   │   ├── models.py  # Modelagem dos dados
   │   ├── routes.py  # Rotas da API
   │   ├── services.py  # Lógica de negócio
   ├── 📁 docs  # Documentação
   ├── 📁 tests  # Testes
   ├── 📄 README.md  # Este arquivo
   ├── 📄 .gitignore  # Arquivos ignorados pelo Git
   ├── 📄 requirements.txt  # Dependências do projeto
```

## 🛠️ Instalação e Execução

### Pré-requisitos

- Python 3.10+
- Pip (gerenciador de pacotes do Python)

### Passos para rodar o projeto

```bash
# Clone este repositório
git clone https://github.com/seu-usuario/devchallenge.git

# Acesse a pasta do projeto
cd devchallenge

# Instale as dependências
pip install -r requirements.txt

# Execute o projeto
python src/app.py
```

## ✅ Funcionalidades

- [x] Criar e gerenciar projetos
- [ ] Criar sociedade com grupo de amigos
- [x] Amigos "compram" ideias de projetos
- [x] Definição de valores e prazos para entrega
- [x] Monitoramento do progresso do projeto
- [x] Penalidade em caso de não entrega

## 📌 Próximos Passos

- Implementação de um painel para gestão dos projetos
- Integração com serviços de pagamento
- Notificações e lembretes automáticos

## 🧪 Testes

```bash
# Executar testes
pytest tests/
```

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

