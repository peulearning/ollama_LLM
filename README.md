# Ollama LLM 🤖

Olá, saudações!

Este projeto tem como finalidade explorar boas práticas de programação, além de aplicar conhecimentos específicos na linguagem Python. Utilizamos FastAPI para criar um servidor web e TinyLlama para realizar requests a um modelo de linguagem local. Este trabalho está sendo desenvolvido no contexto de um projeto pessoal para facilitar interações com inteligência artificial em tempo real.

### 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Consulte Implantação para saber como implantar o projeto.

### 📋 Pré-requisitos & 🔧 Instalação

Para instalar e executar este projeto, você precisará do Python instalado em sua máquina.

    Verifique se você possui o Python instalado:
        Você pode verificar a versão do Python com o seguinte comando:

    bash

```
python --version
```

Instale as dependências do projeto:

    No terminal, execute o seguinte comando:

bash
```
pip install -r requirements.txt
```

Execute o servidor:

    Após a instalação, você pode iniciar o servidor FastAPI com o seguinte comando:

bash
```
    uvicorn main:app --reload
```

```
    Acesse a API:
        Abra seu navegador e acesse http://localhost:8000/docs para visualizar a documentação interativa da API.
```

### 🔩 Análise de Testes de Funcionalidade

```
Terminal
```

Teste de Resposta do Modelo:

```
    Cenário:
        Um usuário faz uma requisição para o modelo de linguagem.
        O servidor processa a solicitação e retorna uma resposta gerada pelo modelo.
```

Teste de Performance:

```
    Cenário:
        Múltiplas requisições simultâneas são feitas ao servidor.
    Verificação:
        Confirma se o servidor consegue lidar com várias requisições ao mesmo tempo.
        Garante que as respostas são geradas em um tempo aceitável.
```

### 🛠️ Construído com

Mencione as ferramentas que você usou para criar seu projeto

    Python - Linguagem de Programação
    FastAPI - Framework para Construção de APIs
    TinyLlama - Modelo de Linguagem para Respostas Locais

### 🖇️ Colaborando

Por favor, leia o COLABORACAO.md para obter detalhes sobre o nosso código de conduta e o processo para nos enviar pedidos de solicitação.

### 📌 Versão

(0.1.0) - 26-10-2024 (Elaboração Inicial do Servidor) <br> (0.2.0) - 28-10-2024 (Implementação de Respostas da IA)

### ✒️ Autores

Mencione todos aqueles que ajudaram a levantar o projeto desde o seu início

    Pedro Henrique (EU) - Desenvolvedor do Ollama LLM

Você também pode ver a lista de todos os colaboradores que participaram deste projeto.

### 📄 Licença

Este projeto está sob a licença (sua licença) - veja o arquivo LICENSE.md para detalhes.

⌨️ com ❤️ por Pedrão Ribeiro 😊
