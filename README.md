# Questionário de Perfil do Cliente - Liberta Investimentos

## Descrição

Este é um questionário interativo desenvolvido para a **Liberta Investimentos** com o objetivo de coletar informações detalhadas sobre o perfil dos clientes para criar estratégias de investimento personalizadas.

## Características

### ✨ Funcionalidades Principais

- **9 Seções Completas**: Perfil do cliente, cônjuge, dependentes, patrimônio, experiência, objetivos, liquidez, tributação e relacionamento
- **Interface Dinâmica**: Campos que aparecem/desaparecem baseados nas seleções do usuário
- **Listas Suspensas Inteligentes**: Regime de casamento, grau de parentesco, objetivos de investimento, etc.
- **Gerenciamento de Dependentes**: Adicionar/remover dependentes dinamicamente
- **Barra de Progresso**: Mostra o progresso do preenchimento em tempo real
- **Validação de Campos**: Campos obrigatórios claramente marcados
- **Design Responsivo**: Funciona perfeitamente em desktop, tablet e mobile

### 🎨 Identidade Visual

- **Cores**: Verde (#22c55e) e preto (#000000) da Liberta Investimentos
- **Tipografia**: Moderna e profissional
- **Layout**: Cards organizados com ícones temáticos
- **Animações**: Transições suaves e micro-interações

### 📱 Responsividade

- Layout adaptativo para diferentes tamanhos de tela
- Grid responsivo para campos de formulário
- Navegação otimizada para dispositivos móveis

## Tecnologias Utilizadas

- **React 18**: Framework principal
- **Vite**: Build tool e servidor de desenvolvimento
- **Tailwind CSS**: Framework de CSS utilitário
- **Shadcn/UI**: Componentes de interface
- **Lucide React**: Ícones modernos

## Como Usar

### Desenvolvimento

1. **Instalar dependências**:
   ```bash
   npm install
   ```

2. **Iniciar servidor de desenvolvimento**:
   ```bash
   npm run dev
   ```

3. **Acessar a aplicação**:
   Abra http://localhost:5173 no navegador

### Produção

1. **Gerar build de produção**:
   ```bash
   npm run build
   ```

2. **Os arquivos estarão na pasta `dist/`**

3. **Para servir localmente**:
   ```bash
   npm run preview
   ```

## Estrutura do Questionário

### 1. 👤 Perfil do Cliente
- Nome completo, data de nascimento, profissão
- Estado civil com regime de casamento dinâmico
- Esporte preferido e hobbies

### 2. 💍 Cônjuge
- Informações do cônjuge/companheiro(a)
- Identificação do pilar financeiro da família

### 3. 👨‍👩‍👧 Dependentes
- Lista dinâmica de dependentes
- Grau de parentesco com opções pré-definidas
- Funcionalidade de adicionar/remover

### 4. 💰 Patrimônio e Renda
- Renda mensal detalhada
- Outras fontes de renda com campos condicionais
- Patrimônio e dívidas

### 5. 📈 Experiência e Perfil de Investidor
- Experiência prévia em investimentos
- Grau de conhecimento e tolerância ao risco
- Reação a crises do mercado

### 6. 🎯 Objetivos Financeiros
- Objetivo principal dos investimentos
- Prazos e rentabilidade esperada
- Preferência entre renda passiva e crescimento

### 7. ⏰ Liquidez e Necessidades Específicas
- Necessidades de liquidez
- Tempo de investimento
- Restrições de produtos

### 8. 📋 Tributação e Planejamento Sucessório
- Preferências fiscais
- Interesse em planejamento sucessório
- Testamento e herança

### 9. 💬 Comportamento e Relacionamento
- Forma preferida de comunicação
- Frequência de atualizações
- Estilo de decisão de investimento

## Funcionalidades Dinâmicas

### Campos Condicionais
- **Regime de Casamento**: Aparece apenas se estado civil for "Casado(a)" ou "União Estável"
- **Campo "Outro"**: Disponível em várias listas suspensas para opções personalizadas
- **Outras Fontes de Renda**: Campo de texto aparece se selecionado "Sim"

### Gerenciamento de Dependentes
- Botão "Adicionar Dependente" cria novos cards
- Botão "Remover" em cada dependente
- Lista de grau de parentesco com opções até segundo grau

### Navegação Inteligente
- Botões "Anterior" e "Próximo" para navegação
- Barra de progresso atualizada automaticamente
- Último botão muda para "Enviar Questionário"

## Personalização

O questionário foi desenvolvido seguindo a identidade visual da Liberta Investimentos e pode ser facilmente personalizado:

- **Cores**: Modificar as variáveis CSS no arquivo de estilos
- **Logo**: Substituir o logo no cabeçalho
- **Campos**: Adicionar/remover campos editando os componentes React
- **Validações**: Implementar validações adicionais conforme necessário

## Suporte

Para dúvidas ou suporte técnico, entre em contato com a equipe de desenvolvimento.

---

**© 2024 Liberta Investimentos - Questionário de Perfil do Cliente**  
*Sua liberdade financeira começa aqui!*
