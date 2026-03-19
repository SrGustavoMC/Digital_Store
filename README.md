# Loja Digital

## Visão Geral

Loja Digital é uma aplicação de e-commerce front-end projetada com ênfase na manutenção, escalabilidade e práticas modernas de desenvolvimento. O projeto implementa uma arquitetura modular usando componentes reutilizáveis, permitindo desenvolvimento eficiente e experiência consistente do usuário na aplicação.

## Pilha de Tecnologia

- React
- Vite
- JavaScript
- Tailwind CSS
- React Router
- ESLint

## Arquitetura

O projeto segue uma arquitetura orientada a componentes, promovendo separação de responsabilidades e reutilização de código.

```
loja-drip/
├── public/
├── src/
│   ├── assets/        # Recursos estáticos (imagens, ícones, etc.)
│   ├── components/    # Componentes de UI reutilizáveis
│   ├── pages/         # Páginas da aplicação (nível de roteamento)
│   ├── styles/        # Estilos globais e escopados
│   ├── App.jsx        # Componente raiz
│   └── main.jsx       # Ponto de entrada da aplicação
├── doc/               # Arquivos de documentação
├── index.html
├── package.json
└── vite.config.js
```

## Recursos

- Interface de listagem de produtos
- Visualização detalhada do produto
- Layout responsivo para múltiplos tamanhos de tela
- Componentes de UI reutilizáveis
- Roteamento do lado cliente com React Router

## Começando

### Pré-requisitos

- Node.js 16 ou superior
- npm ou yarn

### Instalação

```bash
git clone <repository-url>
cd loja-drip
npm install
```

### Desenvolvimento

```bash
npm run dev
```

A aplicação estará disponível em:
http://localhost:5173

### Build de Produção

```bash
npm run build
```

## Qualidade do Código

- ESLint está configurado para impor padrões de codificação
- Estrutura de pastas organizada para melhorar a manutenção
- Separação clara entre UI, lógica e ativos

## Implantação

O projeto inclui configuração para implantação no Vercel, permitindo publicação simplificada e escalabilidade.
