# 🏨 Hotel Terabithia - Sistema de Gestão Interna

O **Hotel Terabithia** é uma plataforma interna de operações hoteleiras projetada para facilitar o dia a dia dos colaboradores. O sistema foca em uma arquitetura modular, onde cada funcionalidade opera como um subprograma independente, garantindo organização e escalabilidade.

---

## 🚀 Funcionalidades

O sistema é composto por módulos integrados que abrangem desde o check-in até a logística de eventos:

### 1. 🛏️ Reservas de Quartos
*   Validação de diárias (limite de 30 dias).
*   Cálculo automático baseado no tipo de quarto:
    *   **Standard:** Fator 1.00
    *   **Executivo:** Fator 1.35
    *   **Luxo:** Fator 1.65
*   Mapa de ocupação visual em grade 4x5.

### 2. 👥 Cadastro de Hóspedes
*   Gestão de até 15 hóspedes em memória.
*   Pesquisa avançada por nome exato ou prefixo.
*   Ordenação alfabética (A-Z) para relatórios.
*   Operações de atualização e remoção por índice.

### 3. 🎭 Gestão de Eventos (Pipeline)
*   **Auditórios:** Seleção inteligente entre o auditório *Laranja* (com cadeiras adicionais) e *Colorado*.
*   **Agenda:** Validação de horários diferenciados para dias de semana e finais de semana.
*   **Equipe:** Cálculo automático de garçons necessários por número de convidados e duração.
*   **Buffet:** Cálculo de custos de café, água e salgados.

### 4. ❄️ Manutenção e Logística
*   **Ar-Condicionado:** Comparador de orçamentos entre diferentes empresas, calculando descontos por quantidade e taxas de deslocamento.
*   **Abastecimento:** Análise econômica entre Álcool e Gasolina para a frota do hotel (Regra dos 70%).

---

## 🛠️ Tecnologias Utilizadas

*   **HTML5**
*   **JavaScript (ES6+)**
*   **Arquitetura:** Decomposição em módulos coesos e funções de responsabilidade única.

---

## 📋 Como Executar

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/seu-usuario/hotel-terabithia.git](https://github.com/seu-usuario/hotel-terabithia.git)
    ```
2.  Abra o arquivo `hotel.html` em qualquer navegador moderno.
3.  Utilize as credenciais padrão:
    *   **Usuário:** Seu nome
    *   **Senha:** `2678`

---

## 📐 Estrutura de Arquivos
```text
├── hotel.html              # Core do sistema, menu principal e reservas
├── cadastrodehospedes.html  # Módulo independente de gestão de hóspedes
└── assets/                 # (Opcional) Imagens e ícones
