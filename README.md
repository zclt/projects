# ZCLT Projects

Site de documentação estática para os projetos pessoais ZCLT, construído com MkDocs e tema Material.

## 📋 Descrição

Este repositório contém a documentação dos projetos ZCLT, organizada em um site estático gerado a partir de arquivos Markdown. O site utiliza MkDocs com o tema Material para proporcionar uma experiência de navegação moderna e responsiva.

## 🚀 Projetos Documentados

| Projeto | Tipo | Descrição |
|---------|------|-----------|
| [Gastoz](docs/gastoz.md) | Finanças | Sistema de gestão financeira |
| [Mercado](docs/mercado.md) | Cotidiano | Aplicativo para o dia a dia |
| [Tô na vaca](docs/to-na-vaca.md) | Galera | Controle de contas entre amigos |
| [Planice](docs/planice.md) | Finanças | Planejamento financeiro |

## 🛠️ Tecnologias

- **MkDocs** - Gerador de sites estáticos
- **Material Theme** - Tema moderno para MkDocs
- **Markdown** - Formato de escrita
- **mkdocs-awesome-pages-plugin** - Plugin para organização de páginas

## 📁 Estrutura do Projeto

```
.
├── docs/                   # Documentação em Markdown
│   ├── index.md           # Página inicial
│   ├── gastoz.md          # Documentação do Gastoz
│   ├── mercado.md         # Documentação do Mercado
│   ├── to-na-vaca.md      # Documentação do Tô na vaca
│   └── planice.md         # Documentação do Planice
├── public/                # Site estático gerado
├── mkdocs.yml            # Configuração do MkDocs
├── requirementes.txt      # Dependências Python
└── README.md             # Este arquivo
```

## 🚦 Instalação e Uso

### Pré-requisitos

- Python 3.7+
- pip

### Instalação

```bash
# Clonar o repositório
git clone https://github.com/zucolotto/zclt-projects.git
cd zclt-projects

# Instalar dependências
pip install -r requirementes.txt
```

### Desenvolvimento

```bash
# Servir localmente
mkdocs serve

# Construir site estático
mkdocs build

# Deploy
mkdocs gh-deploy
```

## 🎨 Recursos

- ✅ Navegação com abas e seções
- ✅ Plugin de busca integrado
- ✅ Design responsivo
- ✅ Suporte a código, tabelas e notas
- ✅ URLs amigáveis
- ✅ Tema Material personalizado

## 📝 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adicionando nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abrir um Pull Request

---

**ZCLT Projects** © 2026
