# 🏥 Checklist Leito Seguro - Cardiologia

Sistema web desenvolvido para auxiliar profissionais da **enfermagem e engenharia clínica** na verificação de integridade e segurança dos leitos hospitalares, promovendo uma **gestão mais eficiente e segura dos ambientes de internação**.

---

## Sobre o Projeto

O **Checklist Leito Seguro** é uma aplicação web responsiva criada para permitir que profissionais realizem a **checagem diária dos leitos de cardiologia**, registrando informações sobre:
- Condições do leito e sua estrutura;
- Itens da cabeceira e equipamentos médicos;
- Condições do quarto e do banheiro;
- Observações e pendências encontradas.

O sistema foi desenvolvido com foco em **usabilidade, agilidade e segurança das informações**.

---

## Como Acessar o Sistema

Para acessar o sistema, utilize as seguintes credenciais de teste:

| Campo | Valor |
|--------|--------|
| **Usuário** | `admin` |
| **Senha** | `1234` |

1. Acesse o link: [https://checklistleitoseguro.netlify.app](https://checklistleitoseguro.netlify.app)  
2. Insira o usuário e senha acima.  
3. Após o login, você será redirecionado para a tela principal do checklist.

> Essas credenciais são apenas para fins de demonstração no ambiente de testes (MVP).

---

## Funcionalidades

**Login de Acesso**  
- Autenticação simples com usuário e senha.  
- Exibição do nome do profissional logado.

**Formulário de Checklist Completo**  
- Identificação do profissional e do leito.  
- Seleção de turno e data.  
- Itens divididos por seções:
  - Leito
  - Cabeceira
  - Quarto
  - Banheiro

**Feedback Visual**  
- Itens com problema aparecem destacados em amarelo.  
- Modal de confirmação após o envio do checklist.

**Upload de Arquivos**  
- Permite anexar **foto ou vídeo** do leito ou equipamento.

**Visualização dos Registros do Dia**  
- Lista de todos os checklists salvos localmente no navegador (via `localStorage`).  
- Ícones de status indicam se o leito possui pendências ou está em condições ideais.

**Design Responsivo**  
- Interface construída com **Tailwind CSS**, adaptada para uso em computadores, tablets e smartphones.

---

## Tecnologias Utilizadas

| Tecnologia | Finalidade |
|-------------|-------------|
| **HTML5** | Estrutura do sistema |
| **Tailwind CSS** | Estilização e layout responsivo |
| **JavaScript (ES Modules)** | Lógica e manipulação do DOM |
| **LocalStorage** | Armazenamento local dos checklists |
| **Netlify** | Hospedagem do sistema online |

---


