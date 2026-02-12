# 🚀 Origin Data

Bem-vindos ao hub de tecnologia da **Origin Data**. Somos um time focado em automação, inteligência de dados e desenvolvimento de software de alta performance.

---

### 🌐 Conecte-se conosco
* **Site Oficial:** [origindata.com.br](http://origindata.com.br) 
* **Facebook:** [Origin Data no Facebook](https://facebook.com/origindata)

---

### 🛠 Nossa Stack de Desenvolvimento

| Front-end | Back-end & Automação | Infra & DevOps |
| :--- | :--- | :--- |
| Next.js / React | Node.js | Docker |
| Tailwind CSS | n8n | Traefik |
| Zod / Iconify | APIs / Webhooks | GitHub Actions |

---

### 📂 Estrutura de Branches e Workflow

Na **Origin Data**, seguimos um fluxo rigoroso para garantir que o código em produção nunca quebre:

#### 1. Hierarquia de Branches
* **`main`**: Código em **Produção**. Reflete a versão mais estável e pública dos nossos sistemas.
* **`dev`**: Ambiente de **Integração**. É onde unimos o trabalho de todos os desenvolvedores para testes.
* **`nome-do-desenvolvedor/task`**: Branches de trabalho individual.
    * *Exemplos:* `dev-front/header-ajuste` ou `dev-back/webhook-clickup`.

#### 2. Ciclo de Desenvolvimento (Passo a Passo)
1.  **Start:** O desenvolvedor cria sua branch de trabalho a partir da `dev`.
2.  **Trabalho:** Realiza os commits e envia para o GitHub.
3.  **PR para Dev:** Abre um **Pull Request** da sua branch pessoal para a `dev`.
4.  **Review:** O time de Front ou Back revisa o código para garantir qualidade.
5.  **Merge Dev:** O código é integrado na `dev`.
6.  **Merge Final:** Após validação em `dev`, o responsável (ou DevOps) realiza o merge da `dev` para a **`main`**.

---

### 👥 Nosso Time
* **Front-end:** 2 Desenvolvedores (Next.js & Tailwind)
* **Back-end:** 1 Desenvolvedor (Node.js & Automações)
* **DevOps:** 1 Especialista (Infra & Deploy)


### BRANCHS

feature/

Criada a partir da dev.

Exemplo: feature/login-page, feature/payment-api.

Cada nova funcionalidade ou melhoria deve ter sua própria branch.

bugfix/

Também criada a partir da dev.

Exemplo: bugfix/fix-navbar, bugfix/api-timeout.

Usada para corrigir problemas que não estão em produção ainda.

hotfix/

Criada a partir da main.

Exemplo: hotfix/security-patch, hotfix/fix-prod-error.

Usada para corrigir problemas críticos diretamente em produção.



---

### 📋 Avisos Importantes
* **Não faça push direto na `main` ou `dev`.** Sempre use Pull Requests.
* Vincule suas Issues aos Pull Requests para manter o **GitHub Project** atualizado.

> "Transformando dados em processos inteligentes." 💡
