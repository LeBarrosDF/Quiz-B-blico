**📘 A Bíblia em Perguntas e Respostas**
Aplicativo de Quiz Bíblico – React Native + FastAPI + MySQL
📖 Sobre o Projeto

A Bíblia em Perguntas e Respostas é um aplicativo mobile de aprendizado bíblico baseado no formato de quiz. 
O objetivo é proporcionar estudo e memorização da palavra de Deus de forma prática, interativa e gamificada, semelhante ao estilo de apps como Duolingo.

Este projeto está sendo desenvolvido inicialmente como um MVP com foco nas funcionalidades essenciais para o aprendizado por meio de perguntas aleatórias, alternativas e pontuação básica.

**✨ Funcionalidades do MVP**

Exibir pergunta aleatória do banco de dados

Mostrar alternativas de múltipla escolha

Indicar respostas corretas (em versão posterior)

Botão Próxima Pergunta

Integração total entre:

Frontend (React Native)

Backend (FastAPI - Python)

Banco de dados MySQL

**🎯 Objetivo Principal**

Desenvolver um app educacional simples, bonito e acessível que permita:

Estudar a Bíblia de maneira interativa

Avançar por pontos e níveis

Aprender com feedback imediato

Registrar progresso (em versões futuras)

**🧱 Arquitetura do Projeto**
📦 Quiz App
 ┣ 📂 backend (FastAPI)
 ┣ 📂 frontend (React Native)
 ┗ 📂 database (MySQL)

🔧 Tecnologias Utilizadas
Frontend

React Native

NativeWind / Tailwind CSS

Fetch API

Backend

Python

FastAPI

SQLAlchemy

Uvicorn

Banco

MySQL

**🚀 Como Executar o Projeto**
🔹 1. Clonar o Repositório
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

🖥 Executando o Backend (FastAPI)
🔹 Instalar dependências
pip install -r requirements.txt

🔹 Rodar o servidor
uvicorn app:app --reload


O backend ficará disponível em:

http://localhost:8000

**📱 Executando o Frontend (React Native)**
🔹 Instalar dependências
npm install

🔹 Iniciar o app
npm start


Depois:

Pressione a para Android

Pressione i para iOS (se estiver em MacOS)

🗄 Banco de Dados

O MySQL contém:

Tabela: perguntas

Tabela: alternativas

A API entrega uma estrutura como:

{
  "id": 1,
  "pergunta": "Quem construiu a arca?",
  "alternativas": [
    { "id": 1, "texto": "Noé", "correta": true },
    { "id": 2, "texto": "Moisés", "correta": false }
  ]
}

🗺 Roadmap (Próximas Entregas)

 Sistema de pontos

 Cadastro e login

 Ranking de jogadores

 Modo “Estudo por Livro da Bíblia”

 Personagens 3D motivacionais

 Versão Premium sem anúncios

 Interface mais avançada

 Sistema de níveis

📄 Licença

MIT License – sinta-se livre para estudar, modificar, melhorar e contribuir!

**❤️ Contribuição**

Sinta-se à vontade para abrir issues, enviar pull requests ou sugerir melhorias.

**🙏 Agradecimentos**

Este projeto tem como propósito auxiliar pessoas que desejam estudar a Bíblia de maneira prática e moderna.
