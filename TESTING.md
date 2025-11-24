# Registros de Testes – Página de Login Full Dev

## 1. Informações gerais

- **Projeto:** Página de Login Full Dev  
- **Descrição:** Página de login desenvolvida em HTML e CSS para trabalho de front-end  
- **Responsável pelos testes:** Luan Lázaro  
- **Data dos testes:** 24/11/2025  
- **Tipo de testes:** Testes manuais (visuais e funcionais)

---

## 2. Ambiente de teste

- **Sistema operacional:** Windows 10
- **Navegadores utilizados:**
  - Google Chrome (versão mais recente)
  - Microsoft Edge (versão mais recente)
- **Resoluções testadas:**
  - 1920 x 1080 (desktop)
  - 1366 x 768 (notebook)
  - ~430 x 932 (modo celular no inspetor do navegador)

---

## 3. Roteiro de testes

### 3.1. Layout da tela de login

| ID  | Cenário                                       | Passos                                                                 | Resultado esperado                                                              | Resultado obtido | Status |
|-----|-----------------------------------------------|------------------------------------------------------------------------|---------------------------------------------------------------------------------|------------------|--------|
| L01 | Página carrega corretamente                   | Acessar o arquivo `index.html` no navegador                           | Tela de login exibida sem erros visuais ou mensagens de erro do navegador      | OK               | ✅     |
| L02 | Elementos principais visíveis                 | Verificar logo, título, campos de login e botão                        | Todos os elementos aparecem alinhados e legíveis                               | OK               | ✅     |
| L03 | Alinhamento do formulário                     | Observar a posição do formulário na tela                               | Formulário centralizado (ou conforme proposto no layout do trabalho)           | OK               | ✅     |
| L04 | Cores e fontes                                | Comparar com o layout planejado / protótipo                           | Cores, fontes e tamanhos consistentes com o design planejado                   | OK               | ✅     |

---

### 3.2. Funcionalidade básica da tela

> Observação: como o projeto é apenas front-end (HTML + CSS), não há validação real no back-end. Os testes consideram apenas o comportamento visual/esperado da interface.

| ID  | Cenário                                    | Passos                                                                 | Resultado esperado                                                              | Resultado obtido | Status |
|-----|--------------------------------------------|------------------------------------------------------------------------|---------------------------------------------------------------------------------|------------------|--------|
| F01 | Digitar usuário e senha                    | Preencher os campos de usuário e senha                                | Campos aceitam texto normalmente                                                | OK               | ✅     |
| F02 | Clique no botão de login                   | Clicar no botão principal de login                                    | Botão reage visualmente (hover/click) e mantém o layout estável                | OK               | ✅     |
| F03 | Links auxiliares (ex: “Esqueci a senha”)   | Clicar nos links presentes na página (se existirem)                   | Links redirecionam para a página correta ou exibem o comportamento esperado    | OK               | ✅     |
| F04 | Acessibilidade básica com teclado          | Usar TAB para navegar entre campos e botão de login                   | A navegação segue a ordem: usuário → senha → botão → links (se houver)         | OK               | ✅     |

---

### 3.3. Responsividade

| ID  | Cenário                             | Passos                                                                        | Resultado esperado                                                                | Resultado obtido | Status |
|-----|-------------------------------------|-------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|------------------|--------|
| R01 | Visualização em resolução desktop  | Maximizar o navegador (1920 x 1080)                                          | Layout ocupa bem o espaço, sem quebra de elementos ou barras de rolagem estranhas | OK               | ✅     |
| R02 | Visualização em notebook           | Ajustar janela para ~1366 x 768                                              | Layout continua organizado, sem textos cortados                                   | OK               | ✅     |
| R03 | Visualização em modo celular       | Abrir DevTools (F12) → ativar modo responsivo e escolher ~430 x 932 (mobile) | Formulário ainda legível, sem elementos muito pequenos ou cortados                | OK               | ✅     |

---

## 4. Problemas encontrados

_No momento da execução dos testes descritos acima, **não foram identificados problemas críticos** que impedissem o uso da página de login._

Se forem encontrados problemas futuramente, registrar aqui:

- **ID do problema:**  
- **Descrição:**  
- **Passos para reproduzir:**  
- **Situação:** Aberto / Corrigido  
- **Data da correção:**  

---

## 5. Conclusão

A versão atual da **Página de Login Full Dev** foi testada manualmente em diferentes
resoluções e navegadores. Do ponto de vista de **layout e comportamento básico da interface**,
a página atendeu aos objetivos do trabalho proposto na faculdade.
 
