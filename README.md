# TaskManager

## Visão Geral do Projeto

**Nome do Projeto:** TaskManager

**Descrição:** O TaskManager é uma aplicação de gerenciamento de tarefas que permite aos usuários organizar, priorizar e monitorar suas tarefas e projetos. O sistema visa melhorar a produtividade e a colaboração, oferecendo uma interface intuitiva e funcionalidades avançadas.

**Licença:** MIT

**Autor:** João P M Morais

## Requisitos do Sistema

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- Git (opcional, se você deseja clonar o repositório)

## Instalação

1. Clone este repositório:

```bash
git clone https://github.com/seu_usuario/taskmanager.git
```

2. Navegue até o diretório do projeto:

```bash
cd taskmanager
```

3. Copie o arquivo de ambiente de exemplo e gere uma chave do aplicativo:

```bash
cp .env.example .env
php artisan key:generate
```

4. Inicie o ambiente Docker usando Laravel Sail:

```bash
./vendor/bin/sail up -d
```

5. Execute as migrações do banco de dados:

```bash
./vendor/bin/sail artisan migrate
```

6. Acesse o aplicativo em seu navegador em [http://localhost](http://localhost).

## Licença

Este projeto é licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.

## Contato

- **Email:** [paulomedeiros5000@gmail.com](mailto:paulomedeiros5000@gmail.com)
- **LinkedIn:** [João P M Morais](https://www.linkedin.com/in/joaopmmorais/)
- **Portfólio:** [joaopmmorais.tech](https://joaopmmorais.tech/)
