# 🦜 Indiko - App de Indicações

## 📱 Sobre o App

O **Indiko** é uma plataforma interativa e moderna que recompensa usuários por indicarem amigos. Com uma interface amigável, visual moderno e minimalista, oferece uma experiência altamente intuitiva.

## ✨ Características Principais

### 🎨 Design & UX
- **Paleta de Cores**: Azul vibrante (#007BCE), Verde sucesso (#22C55E), Amarelo destaque (#FACC15), Branco puro (#FFFFFF)
- **Tipografia**: Poppins Bold para títulos, Inter Regular para corpo e UI
- **Mascote**: Tucano "Indiko" com bico multicolorido (amarelo, verde, azul)
- **Interface**: Mobile-first, responsiva e moderna

### 🚀 Funcionalidades

#### 📋 Telas Implementadas:
1. **Tela de Boas-vindas** - Apresentação do app com mascote animado
2. **Cadastro/Login** - Registro e autenticação de usuários
3. **Dashboard Principal** - Visão geral com progresso e estatísticas
4. **Indicação** - Formulário para indicar amigos + compartilhamento
5. **Confirmação** - Feedback visual de indicação enviada
6. **Histórico** - Lista de indicações com filtros por status
7. **Recompensas** - Catálogo de prêmios com sistema de pontos
8. **Ranking** - Classificação dos melhores indicadores
9. **Perfil** - Gerenciamento de dados pessoais e configurações
10. **Ajuda/Suporte** - FAQ e contato direto via WhatsApp

#### 🎯 Recursos Interativos:
- **Gamificação**: Sistema de pontos e medalhas
- **Microinterações**: Transições suaves e animações
- **Progresso Visual**: Barras animadas de progresso
- **Navegação Mobile**: Menu inferior otimizado
- **Compartilhamento Social**: WhatsApp, Instagram, copiar link
- **Notificações**: Sistema configurável de alertas

## 🛠️ Tecnologias Utilizadas

- **Framework**: Next.js 15 com TypeScript
- **Styling**: Tailwind CSS 4
- **Componentes**: shadcn/ui (Radix UI)
- **Fontes**: Google Fonts (Poppins, Inter)
- **Animações**: CSS Animations + Tailwind
- **Responsividade**: Mobile-first design

## 📦 Instalação e Execução

### Pré-requisitos
- Node.js 18+ 
- npm ou yarn

### Passos para Instalação

1. **Extrair o arquivo ZIP**
```bash
unzip indiko-app.zip
cd indiko-app
```

2. **Instalar dependências**
```bash
npm install
# ou
yarn install
```

3. **Executar em desenvolvimento**
```bash
npm run dev
# ou
yarn dev
```

4. **Acessar o aplicativo**
- Abra o navegador em: `http://localhost:3000`
- Para usar a porta 8000: `PORT=8000 npm run dev`

### Comandos Disponíveis

```bash
# Desenvolvimento
npm run dev

# Build para produção
npm run build

# Iniciar produção
npm run start

# Linting
npm run lint
```

## 🏗️ Estrutura do Projeto

```
src/
├── app/                    # Páginas do App Router (Next.js 13+)
│   ├── layout.tsx         # Layout principal
│   ├── page.tsx           # Tela de boas-vindas
│   ├── cadastro/          # Cadastro/Login
│   ├── dashboard/         # Dashboard principal
│   ├── indicacao/         # Indicar amigos
│   ├── confirmacao/       # Confirmação de indicação
│   ├── historico/         # Histórico de indicações
│   ├── recompensas/       # Catálogo de recompensas
│   ├── ranking/           # Ranking de usuários
│   ├── perfil/            # Perfil do usuário
│   └── ajuda/             # Central de ajuda
├── components/
│   ├── indiko/            # Componentes específicos do Indiko
│   │   ├── mascot.tsx     # Mascote Tucano animado
│   │   ├── navigation.tsx # Navegação mobile
│   │   ├── progress-bar.tsx # Barra de progresso
│   │   ├── stats-card.tsx # Cards de estatísticas
│   │   └── reward-card.tsx # Cards de recompensas
│   └── ui/                # Componentes shadcn/ui
└── lib/                   # Utilitários e configurações
```

## 🎨 Componentes Personalizados

### 🦜 Mascot (Tucano Indiko)
- Animações suaves
- Estados: normal, animado, comemorando
- Tamanhos: sm, md, lg, xl

### 📊 ProgressBar
- Animação de preenchimento
- Indicadores visuais de progresso
- Mensagens contextuais

### 📱 MobileNavigation
- Menu inferior fixo
- Indicadores de página ativa
- Ícones personalizados

### 📈 StatsCard
- Cards de estatísticas coloridos
- Indicadores de tendência
- Responsivo e animado

### 🎁 RewardCard
- Cards de recompensas interativos
- Sistema de pontos integrado
- Estados: disponível, bloqueado, resgatado

## 🔧 Integração com Backend

### Pontos de Integração Necessários:

1. **Autenticação**
   - Cadastro de usuários
   - Login/logout
   - Gerenciamento de sessão

2. **Sistema de Indicações**
   - Criar indicação
   - Validar indicações
   - Histórico de indicações

3. **Sistema de Pontos**
   - Calcular pontos
   - Histórico de pontuação
   - Ranking de usuários

4. **Sistema de Recompensas**
   - Catálogo de recompensas
   - Resgate de prêmios
   - Controle de estoque

### Sugestões de Backend:
- **Firebase**: Para prototipagem rápida
- **PostgreSQL + Prisma**: Para produção
- **Node.js + Express**: API REST
- **NextAuth.js**: Autenticação

## 📱 Recursos Mobile

- **PWA Ready**: Pode ser instalado como app
- **Touch Friendly**: Otimizado para toque
- **Offline Support**: Funcionalidades básicas offline
- **Push Notifications**: Suporte a notificações

## 🎯 Próximos Passos

1. **Integração Backend**: Conectar com APIs reais
2. **Autenticação**: Implementar sistema de login
3. **Notificações Push**: Alertas em tempo real
4. **Analytics**: Tracking de eventos
5. **Testes**: Implementar testes automatizados
6. **Deploy**: Configurar CI/CD

## 📞 Suporte

Para dúvidas ou suporte técnico:
- **Email**: suporte@indiko.app
- **WhatsApp**: (11) 99999-9999

## 📄 Licença

Este projeto foi desenvolvido como uma demonstração de aplicativo moderno de indicações.

---

**Desenvolvido com ❤️ para conectar pessoas através de indicações!**
