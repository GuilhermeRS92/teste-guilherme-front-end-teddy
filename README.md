
# Desafio Frontend - Teddy

O desafio consiste em desenvolver uma aplicação web para cadastro de parceiros e empresas externas.

## Tecnologias

- Angular 15
- TypeScript

## Sobre a aplicação

A aplicação está dividida em 5 micro front-ends:

- app-shell (Git: https://github.com/GuilhermeRS92/app-shell) - Casca com autenticação para e rotas para o micro front end, esse projeto roda na porta 4200;
- partners (Git: https://github.com/GuilhermeRS92/partners) - Micro front-end responsável pela visualização e cadastro de parceiros, esse projeto roda na porta 4201;
- companies (Git: https://github.com/GuilhermeRS92/companies) - Micro front-end responsável pela visualização e cadastro de empresas externas, esse projeto roda na porta 4202;
- about (Git: https://github.com/GuilhermeRS92/about) - Micro front-end responsável por informações do projeto, esse projeto roda na porta 4203;

# Instalação

Para rodar o projeto, você deve ter instalado o Node.js.

## Clone o repositório
Clone as aplicações de cada micro front-end:
```bash
$ git clone
```
## Acesse a pasta do projeto no terminal/cmd
```bash
$ cd {{nome-do-projeto}}
```

## Instale as dependências
```bash
$ npm install
```

## Execute cada aplicação aplicação
```bash
$ ng run start
```

# Testes

## Acesse a pasta do projeto no terminal/cmd
```bash
$ cd {{nome-do-projeto}}
```

## Execute os testes de cada aplicação
```bash
$ npm run test
```

Cada aplicação inciará na porta conforme informado no tópico "Sobre a aplicação".

A aplicação principal (app-shell) rodará na porta 4200.

# TODO / TASKS

## Funcionalidades

[x] Página de login com opção "manter conectado". Estimativa: 2 horas \
[x] Página inicial com menu e navegação. Estimativa: 3 horas \
[x] Página de cadastro de parceiro. Estimativa: 4 horas \
[x] Listar todos os parceiros com paginação, editar e deletar. Estimativa: 6 horas \
[x] Página de cadastro de empresa externa. Estimativa: 4 horas \
[x] Listar todas as empresas externas com paginação, editar e deletar. Estimativa: 6 horas \
[ ] Página "Sobre a aplicação". Estimativa: 2 horas \
[x] Funcionalidade de compartilhamento de URL com paginação. Estimativa: 5 horas \
[x] Integração com as APIs para CRUD. Estimativa: 8 horas \
[ ] Implementação de testes unitários. Estimativa: 5 horas \
 \
Infraestrutura  \
[ ] Configurar Docker para a aplicação. Estimativa: 3 horas \
[ ] Deploy no GitHub Pages. Estimativa: 2 horas  \
 \
Documentação e Extras \
[ ] Gravar vídeo de apresentação e subir no YouTube. Estimativa: 2 horas \
[x] Atualizar README com instruções e lista de tarefas. Estimativa: 1 hora

## Autor

- LinkedIn - [Guilherme Ribeiro](https://www.linkedin.com/in/guilhermeribeirosouza/)
- GitHub - [Guilherme Ribeiro](https://github.com/GuilhermeRS92)

Licença
Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.