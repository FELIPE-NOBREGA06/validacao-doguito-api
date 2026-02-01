# Validação Doguito

Um projeto de validação de formulários com tema Doguito, desenvolvido com HTML, CSS e JavaScript vanilla.

## 📋 Sobre o Projeto

Este projeto implementa um sistema de validação de formulários para cadastro de clientes e produtos, com uma interface amigável e responsiva. O projeto utiliza validações em tempo real e feedback visual para o usuário.

## 🎯 Funcionalidades

- ✅ Validação de formulários em tempo real
- ✅ Cadastro de clientes
- ✅ Cadastro de produtos
- ✅ Edição de clientes
- ✅ Listagem de clientes
- ✅ Interface responsiva
- ✅ Feedback visual com modais
- ✅ Tabelas de dados

## 📁 Estrutura do Projeto

```
validacao-doguito/
├── assets/
│   ├── css/
│   │   ├── base/
│   │   │   ├── base.css
│   │   │   ├── _reset.css
│   │   │   └── _variaveis.css
│   │   ├── componentes/
│   │   │   ├── botao.css
│   │   │   ├── cabecalho.css
│   │   │   ├── cartao.css
│   │   │   ├── inputs.css
│   │   │   ├── modal.css
│   │   │   └── tabela.css
│   │   ├── cadastra_cliente.css
│   │   ├── cadastro.css
│   │   ├── cadastro_concluido.css
│   │   ├── cadastro_produto.css
│   │   ├── edita_cliente.css
│   │   ├── edicao_concluida.css
│   │   └── lista_cliente.css
│   └── img/
│       ├── checkmark.svg
│       ├── doguito.svg
│       └── doguitoadm.svg
├── js/
│   ├── app.js
│   └── validacao.js
├── cadastro.html
├── cadastro_concluido.html
├── cadastro_produto.html
├── cadastro_produto_concluido.html
└── README.md
```

## 🚀 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/FELIPE-NOBREGA06/validacao-doguito-api.git
```

2. Abra o arquivo `cadastro.html` no seu navegador ou use um servidor local:
```bash
# Usando Python
python -m http.server 8000

# Ou usando Node.js com http-server
npx http-server
```

3. Navegue pelas páginas de cadastro e listagem

## 📄 Páginas Disponíveis

- **cadastro.html** - Formulário de cadastro de clientes
- **cadastro_concluido.html** - Confirmação de cadastro realizado
- **cadastro_produto.html** - Formulário de cadastro de produtos
- **cadastro_produto_concluido.html** - Confirmação de cadastro de produto
- **lista_cliente.html** - Listagem de clientes cadastrados
- **edita_cliente.html** - Edição de dados de cliente

## 🎨 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e layout responsivo
- **JavaScript Vanilla** - Validações e interatividade
- **SVG** - Ícones e imagens vetoriais

## ✨ Recursos de Validação

O projeto implementa validações para:
- Campos obrigatórios
- Formato de email
- Comprimento mínimo/máximo
- Padrões específicos (CPF, telefone, etc.)
- Feedback em tempo real

## 📝 Estrutura de Arquivos CSS

- **base/** - Estilos base e variáveis globais
- **componentes/** - Estilos de componentes reutilizáveis
- **Páginas específicas** - Estilos customizados por página

## 🔧 Desenvolvimento

Para contribuir com o projeto:

1. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
2. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
3. Push para a branch (`git push origin feature/AmazingFeature`)
4. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT.

## 👤 Autor

Felipe Nóbrega - [@FELIPE-NOBREGA06](https://github.com/FELIPE-NOBREGA06)