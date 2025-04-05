
# Barber Shop UI

Este é o repositório do **Barber Shop UI**, um projeto desenvolvido em Angular para gerenciar agendamentos de atendimento em uma barbearia. O projeto utiliza a biblioteca Angular Material para a construção da interface.

## 💈 Sobre o Projeto

O objetivo deste projeto é fornecer uma interface amigável e eficiente para o agendamento de serviços em uma barbearia. Ele explora conceitos fundamentais do Angular e integra componentes do Angular Material para aprimorar a experiência do usuário.

## 🚀 Funcionalidades

- Agendamento de Serviços
- Gerenciamento de Clientes
- Lista de Serviços com detalhes e preços
- Interface responsiva (mobile e desktop)

## 🛠️ Tecnologias Utilizadas

- [Angular](https://angular.io/)
- [Angular Material](https://material.angular.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [Docker](https://www.docker.com/) (opcional)

## 📁 Estrutura do Projeto

```
barber-shop-ui/
├── src/
│   ├── app/                # Componentes, módulos e serviços Angular
│   ├── assets/             # Imagens e estilos
├── angular.json            # Configurações do Angular CLI
├── package.json            # Dependências e scripts
├── Dockerfile              # Build Docker da aplicação
```

## ⚙️ Pré-requisitos

- Node.js
- Angular CLI
- Docker (opcional)

## ▶️ Como Executar

### Com Angular CLI:

```bash
git clone https://github.com/leoamff/barber-shop-ui.git
cd barber-shop-ui
npm install
ng serve
```

Acesse em `http://localhost:4200/`

### Com Docker:

```bash
docker build -t barber-shop-ui .
docker run -p 4200:80 barber-shop-ui
```

Acesse em `http://localhost:4200/`

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias.

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).

---

**Desenvolvido com 💇‍♂️ por [leoamff](https://github.com/leoamff)**
