# README: Calendário Responsivo

## 📋 Descrição
Este é um projeto de **Calendário Responsivo** em HTML, CSS e JavaScript que permite visualizar meses, alternar para o modo escuro, gerenciar lembretes para dias específicos, destacar finais de semana e feriados, e salvar dados no `localStorage` para manter as informações mesmo após recarregar a página.

---

## 🔑 Funcionalidades
1. **Modo escuro**: Permite alternar o tema da página clicando no ícone da lua 🌙.
2. **Navegação entre meses**: Use os botões para mudar entre os meses anteriores e seguintes.
3. **Finais de semana destacados**: Os dias de sábado e domingo são visualmente destacados.
4. **Feriados**: Datas fixas de feriados são sinalizadas e exibem um tooltip ao passar o mouse.
5. **Lembretes**: Adicione lembretes para dias específicos através de uma interface modal.
6. **Persistência de dados**: Lembretes são salvos no `localStorage` e permanecem mesmo após o fechamento ou recarregamento da página.

---

## 📂 Estrutura do Código

### **HTML**
- **Cabeçalho**: Elementos básicos de definição de idioma (`lang="pt-BR"`), charset e título do projeto.
- **Divs**:
  - `.calendario`: Estrutura principal do calendário.
  - `.calendario-header`: Cabeçalho contendo botões de navegação e o botão de modo escuro.
- **Modal**: `#lembreteModal` para entrada de lembretes, com suporte para salvar ou cancelar.

---

### **CSS**
- **Variáveis de estilo**: Define cores, fontes e propriedades para modos claro e escuro.
- **Design responsivo**: Ajusta layout para dispositivos menores com a regra `@media`.
- **Classes específicas**:
  - `.dark-mode`: Alteração de tema.
  - `.fim-de-semana`, `.feriado`, `.dia-atual`: Estilização especial para certos dias.

---

### **JavaScript**
1. **Definição e inicialização de variáveis**:
   - `dataAtual`: Define o mês e o ano inicial.
   - `feriados`: Lista de feriados fixos com suporte para tooltips.
   - `lembretes`: Armazena lembretes no `localStorage`.

2. **Funções principais**:
   - `renderCalendario`: Renderiza o calendário atual com todos os destaques (fim de semana, feriados, dia atual).
   - `mudarMes(valor)`: Alterna entre meses.
   - `abrirModal(data)`: Abre o modal para adicionar ou editar lembretes de um dia específico.
   - `salvarLembrete`: Salva lembretes no `localStorage`.
   - `fecharModal`: Fecha o modal.
   - `alternarModoEscuro`: Alterna entre os temas claro e escuro.

3. **Eventos**:
   - `DOMContentLoaded`: Garante que o calendário seja renderizado após o carregamento da página.

---

## 🛠️ Instalação
1. Faça o download dos arquivos ou clone o repositório.
2. Abra o arquivo `index.html` em um navegador compatível (Chrome, Edge, Firefox, etc.).
3. Permita o uso do `localStorage` no navegador.

---

## 🚀 Como Usar
1. Abra o calendário.
2. Navegue entre os meses usando os botões "<" e ">".
3. Clique em um dia para abrir o modal de lembretes.
4. Escreva um lembrete e clique em "Salvar".
5. Ative o modo escuro clicando no botão da lua.

---

## 🖥️ Tecnologias Utilizadas
- **HTML5**: Para marcação semântica.
- **CSS3**: Para estilização avançada e modo escuro.
- **JavaScript**: Para lógica e interatividade dinâmica.
- **LocalStorage**: Para persistência de dados.

---

## 🔒 Requisitos
- Navegador moderno com suporte a `localStorage` e compatível com JavaScript.

---

## 📧 Suporte
Se você tiver dúvidas ou problemas, sinta-se à vontade para entrar em contato.

---


 

