# ERPNinja

![Versão](https://img.shields.io/badge/versão-1.0.0-blue)
![Licença](https://img.shields.io/badge/licença-MIT-green)

## 📋 Descrição

ERPNinja é um sistema ERP (Enterprise Resource Planning) completo e moderno, desenvolvido para atender às necessidades de empresas de todos os portes. Com uma arquitetura robusta e escalável, o ERPNinja oferece módulos integrados para gerenciamento de:

- 📦 Estoque e Inventário
- 💰 Financeiro (Contas a Pagar/Receber)
- 🛒 Vendas e CRM
- 🏭 Produção e Manufatura
- 👥 Recursos Humanos
- 📊 Business Intelligence e Relatórios
- 🔄 Integração com E-commerce

## 🚀 Tecnologias

O projeto utiliza um stack tecnológico moderno e robusto:

### Backend
- Laravel 10.x (PHP 8.2+)
- PostgreSQL 16.x
- Redis para cache e filas
- API RESTful

### Frontend
- Vue.js 3.x com Composition API
- Tailwind CSS 3.x
- Inertia.js para SPA

### DevOps
- Docker e Docker Compose
- CI/CD com GitHub Actions
- Testes automatizados com PHPUnit e Jest

## 🛠️ Instalação

### Pré-requisitos
- Docker e Docker Compose
- Git
- Composer (opcional para desenvolvimento local)
- Node.js e NPM (opcional para desenvolvimento local)

### Passos para instalação

```bash
# Clone o repositório
git clone https://github.com/ninjamacosso/erpninja.git
cd erpninja

# Inicie os containers Docker
docker-compose up -d

# Instale as dependências
docker-compose exec app composer install
docker-compose exec app npm install

# Execute as migrações e seeders
docker-compose exec app php artisan migrate --seed

# Compile os assets
docker-compose exec app npm run dev
```

## 📚 Documentação

A documentação completa está disponível na [Wiki do projeto](https://github.com/ninjamacosso/erpninja/wiki).

## 🤝 Contribuição

Contribuições são bem-vindas! Por favor, leia o [guia de contribuição](CONTRIBUTING.md) antes de submeter pull requests.

## 📝 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 📞 Suporte

Para suporte, abra uma issue no GitHub ou entre em contato através do email: suporte@erpninja.com.br