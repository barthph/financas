# Finanças Pessoais - Controle Financeiro Inteligente

## 🎯 Sobre o Projeto

Um site completo de gestão de finanças pessoais, responsivo para móbile e computador, desenvolvido em React com funcionalidades avançadas de controle financeiro.

## 🚀 Funcionalidades Principais

### 💰 Controle de Salário
- Adicionar múltiplas fontes de renda
- Acompanhar ganhos mensais
- Histórico de rendas cadastradas
- Cálculo automático do total mensal

### 💳 Controle de Despesas
- Categorização inteligente de despesas
- 6 categorias pré-definidas: Moradia, Transporte, Alimentação, Saúde, Educação, Lazer
- Resumo por categoria com percentuais
- Histórico detalhado de gastos

### 📊 Outros Gastos
- Registro de gastos extras e imprevistos
- Tipos: Emergência, Presente, Manutenção, Viagem, Compra Especial
- Análise de distribuição por tipo
- Controle de gastos não planejados

### 🏦 Investimentos
- **Reserva Automática de 15%**: Cálculo automático baseado na sobra após despesas
- Múltiplos tipos de investimento: Poupança, CDB, Tesouro Direto, Ações, Fundos
- Acompanhamento de rendimentos
- Cálculo de rentabilidade
- Progresso da meta de reserva

### 📈 Gráficos e Visualizações
- **Evolução dos Investimentos**: Gráfico de linha mostrando crescimento ao longo do tempo
- **Despesas por Categoria**: Gráfico de pizza com distribuição percentual
- **Resumo Financeiro**: Gráfico de barras comparando renda, despesas e sobra
- **Performance dos Investimentos**: Comparação valor inicial vs atual
- **Indicadores de Performance**: Taxa de poupança, sobra mensal, meta de reserva

## 🎨 Características Técnicas

### Responsividade
- ✅ Layout otimizado para desktop
- ✅ Interface adaptada para dispositivos móveis
- ✅ Navegação por abas intuitiva
- ✅ Componentes que se ajustam automaticamente

### Persistência de Dados
- Armazenamento local no navegador (localStorage)
- Dados mantidos entre sessões
- Não requer cadastro ou login

### Interface Moderna
- Design clean e profissional
- Componentes shadcn/ui
- Ícones Lucide React
- Tailwind CSS para estilização
- Animações suaves

## 🛠️ Tecnologias Utilizadas

- **React 18** - Framework principal
- **Vite** - Build tool e dev server
- **Tailwind CSS** - Estilização
- **shadcn/ui** - Componentes de interface
- **Recharts** - Biblioteca de gráficos
- **Lucide React** - Ícones
- **JavaScript** - Linguagem de programação

## 🚀 Como Configurar e Rodar Localmente

Para ter o projeto funcionando em sua máquina local, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    cd financas-pessoais
    ```

2.  **Instale as dependências:**
    Certifique-se de ter o Node.js e o npm (ou pnpm/yarn) instalados em sua máquina. Em seguida, no diretório do projeto, execute:
    ```bash
    npm install --legacy-peer-deps
    # ou pnpm install
    # ou yarn install
    ```

3.  **Inicie o servidor de desenvolvimento:**
    ```bash
    npm run dev
    # ou pnpm run dev
    # ou yarn dev
    ```
    O aplicativo estará disponível em `http://localhost:5173` (ou outra porta disponível).

## 📦 Como Gerar o Build para Produção

Para gerar uma versão otimizada do aplicativo para deploy (por exemplo, em serviços de hospedagem estática como GitHub Pages, Netlify, Vercel):

```bash
npm run build
# ou pnpm run build
# ou yarn build
```

Os arquivos de produção serão gerados na pasta `dist/`.

## 📄 Licença

Projeto desenvolvido para fins educacionais e de controle financeiro pessoal.

---

*Desenvolvido com ❤️ para ajudar no controle financeiro pessoal*

