
# Curso Desenvolvimento Avançado em Angular

Neste repositório estão disponíveis os arquivos de automatização de ambiente que serve de material de apoio do curso **Desenvolvimento Avançado em Angular** oferecido pela plataforma **[desenvolvedor.io](https://desenvolvedor.io)**

## Como utilizar

Para criar rapidamente o ambiente disponibilizamos as imagens Docker dos 3 recursos da aplicação:

- [WebApp SPA Angular](https://hub.docker.com/r/desenvolvedorio/app-spa-curso-angular)
- [API ASP.NET Core](https://hub.docker.com/r/desenvolvedorio/api-aspnet-curso-angular)
- [SQL Server](https://hub.docker.com/r/desenvolvedorio/sql-api-curso-angular)

> **Requisito:** É necessário ter o docker instalado em seu sistema operacional (Linux, Windows ou Mac)

### Disponibilizar apenas o back-end
Rode o comando (apontando a pasta local do arquivo):  
- ` docker-compose -f docker-compose.backend.yml up` 

### Disponibilizar front-end e back-end
Rode o comando (apontando a pasta local do arquivo):  
- ` docker-compose -f docker-compose.fullstack.yml up` 

#### É possível renomear um dos arquivos para 'docker-compose.yml' e rodar o comando mais simplificado:  
- ` docker-compose up` 

#### Para parar a execução no console (executando no modo 'detached'):  
- ` docker-compose down` 

#### Para parar a execução no console (executando no modo 'attached'):  
- <kbd>Crtl</kbd> + <kbd>C</kbd>

## Sobre o curso

A apresentação completa do curso está disponível em nossa plataforma:
**[https://desenvolvedor.io/curso-online-desenvolvimento-avancado-em-angular](https://desenvolvedor.io/curso-online-desenvolvimento-avancado-em-angular)**
## Suporte

Se você é nosso aluno entre em contato pelo nosso suporte [suporte@desenvolvedor.io](mailto:suporte@desenvolvedor.io)
