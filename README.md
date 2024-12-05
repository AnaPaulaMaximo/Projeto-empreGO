![Imagem de Capa](static/img/Header.png)

# EmpreGO! - Sistema de Gestão de Vagas de Emprego

**EmpreGO!** é um sistema web completo para gestão de vagas de emprego, desenvolvido utilizando Flask (Python), MySQL para o banco de dados, e HTML/CSS/JavaScript para a interface de usuário. O sistema permite que empresas publiquem vagas, gerenciem seus status e visualizem candidatos. Administradores têm o controle sobre o cadastro e a gestão das empresas cadastradas.

## Índice
- [Status](#status)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Instalar e Executar o Projeto](#como-instalar-e-executar-o-projeto)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Autores](#autores)
- [Licença](#licença)

## Status
✔ **Concluído** ✔

## Funcionalidades

### Para Usuários:
- **Busca de Vagas**: Permite buscar vagas por palavras-chave no título ou descrição.
- **Visualização de Detalhes da Vaga**: Exibe informações detalhadas sobre uma vaga específica, como descrição, local, salário, tipo de contrato e formato de trabalho.
- **Candidatura a Vagas**: Usuários podem se candidatar às vagas enviando seu currículo (formato PDF).

![gif](static/img/usuarios.gif)

### Para Empresas:
- **Cadastro de Vagas**: Empresas podem criar novas vagas de emprego, incluindo descrição detalhada e requisitos.
- **Gerenciamento de Vagas**: Empresas podem editar, inativar ou excluir suas vagas conforme necessário.
- **Visualização de Candidatos**: Empresas podem visualizar os currículos dos candidatos e gerenciar as candidaturas (remover candidatos, etc.).

![gif](static/img/empresa.gif)

### Para Administradores:
- **Cadastro de Empresas**: Administradores podem cadastrar novas empresas no sistema.
- **Gerenciamento de Empresas**: Administradores podem editar informações de empresas, ativar/desativar empresas e excluir empresas do sistema.
- **Painel Administrativo**: Exibe uma visão geral das empresas cadastradas, tanto ativas quanto inativas.

![gif](static/img/adm.gif)

## Tecnologias Utilizadas

- ![MYSQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
- ![PYTHON](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
- ![JAVASCRIPT](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
- ![BOOTSTRAP](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

## Como Instalar e Executar o Projeto

### 1. Pré-requisitos
Certifique-se de que você possui os seguintes componentes instalados:
- Python 3.x (preferencialmente 3.7 ou superior)
- MySQL (servidor e cliente configurados)
- pip (gerenciador de pacotes do Python)
- Um ambiente virtual (opcional, mas recomendado)

### 2. Configuração Inicial

Clone o repositório:
```bash
git clone <url-do-repositório>
cd <nome-da-pasta-do-projeto> 
```
### 2. Configuração do Banco de Dados
Certifique-se de que o servidor MySQL está rodando em sua máquina.

Crie um banco de dados para o sistema:

```CREATE DATABASE emprego;```

### 3. Configure as credenciais do banco de dados no arquivo config.py:
```DB_HOST = 'localhost'
DB_USER = 'seu_usuario'
DB_PASSWORD = 'sua_senha'
DB_NAME = 'emprego'
```

### 4. Estrutura do Projeto:
- app.py: Arquivo principal que contém as rotas do sistema.
- templates/: Diretório contendo os arquivos HTML para as páginas.
- static/: Diretório contendo os arquivos estáticos (CSS, JavaScript, imagens).
- uploads/: Diretório onde os currículos enviados são armazenados.
- config.py: Arquivo de configuração para o banco de dados e chaves secretas.
- db_functions.py: Contém funções utilitárias para manipulação do banco de dados.

## Autores

- Ana Paula Maximo - GitHub - github.com/AnaPaulaMaximo

## Licença
Este projeto é de uso livre para fins educacionais e pode ser adaptado conforme necessário. Qualquer contribuição ou melhoria é bem-vinda!


