<h1 align="center">
    <img  src="https://github.com/user-attachments/assets/3fc69cb3-34c1-42af-a25d-39e6d1498f29" width="100">
</h1>
<h2 align="center">Documentação do Projeto</h2>

## Guia de Contribuição para `mf-auth`

Bem-vindo ao projeto `mf-auth`! Este guia fornece instruções para que nossa equipe colabore no desenvolvimento da API de autenticação de usuários de maneira organizada e eficaz. Siga as diretrizes abaixo para garantir que o projeto se mantenha estruturado e fácil de manter.

---

### 📑 Como Contribuir

#### 1. Reportando Problemas (Issues)
- **Verificação Prévia**: Antes de abrir uma nova Issue, consulte as Issues abertas para evitar duplicação.
- **Descrição Clara**: Inclua uma descrição detalhada, passos para reproduzir o problema, mensagens de erro e informações do ambiente (ex.: sistema operacional, versão do Java).
- **Uso de Labels**: Adicione labels apropriadas para ajudar na organização e priorização (ex.: `🐞 Bug`, `🚀 Feature Request`, `📝 Documentation`).

#### 2. Sugerindo Melhorias e Funcionalidades
- Abra uma Issue com a label `🚀 Feature Request` para sugerir novas funcionalidades.
- Descreva o problema ou a motivação da melhoria.
- Consulte o líder do projeto antes de implementar funcionalidades significativas.

#### 3. Configurando o Ambiente Local
- **Fork** o repositório da organização para seu perfil.
- **Clone** o repositório em sua máquina:
  ```bash
  git clone https://github.com/sua-conta/mf-auth.git
  ```
  
- Crie uma nova branch para sua contribuição:
  ```bash
  git checkout -b minha-contribuicao
  ```
  

#### 4. Desenvolvendo e Comitando Mudanças
- **Padrões de Código**: Mantenha o padrão de formatação do projeto.
- **Documentação**: Para cada nova funcionalidade ou mudança significativa, atualize a documentação.

---

### 📐 Convenções de Commits

Para manter o histórico de commits organizado, siga as convenções abaixo:

#### Estrutura do Commit
Utilize o formato: <tipo>: <descrição breve>


#### Tipos de Commits

- **feat**: Adiciona uma nova funcionalidade.
  - Exemplo:
    ```bash
    feat: adiciona endpoint para autenticação de usuários
    ```
  
- **fix**: Corrige um bug.
  - Exemplo:
    ```bash
    fix: corrige erro de autenticação com tokens inválidos
    ```
  
- **docs**: Alterações na documentação.
  - Exemplo:
    ```bash
    docs: atualiza README com novas instruções de instalação
    ```
    
- **style**: Mudanças de formatação (espaços, vírgulas, etc) que não afetam a lógica.
  - Exemplo:
    ```bash
    style: ajusta formatação no arquivo de autenticação
    ```

    
- **refactor**: Alterações no código que não corrigem bugs nem adicionam funcionalidades.
  - Exemplo:
    ```bash
    refactor: otimiza função de verificação de sessão
    ```

    
- **test**: Adiciona ou modifica testes.
  - Exemplo:
    ```bash
    test: adiciona testes para autenticação de usuário
    ```

    
- **chore**: Atualizações no build ou em configurações de infraestrutura.
  - Exemplo:
    ```bash
    chore: atualiza dependências no pom.xml
    ```
    

#### Boas Práticas
- **Commits Frequentes**: Faça commits pequenos e frequentes. Isso facilita revisões e manutenção.
- **Mensagens Claras**: Seja claro e objetivo nas mensagens de commit.
- **Agrupe Alterações Relacionadas**: Evite fazer várias mudanças não relacionadas no mesmo commit.

---

### 🧪 Testes

- **Testes Unitários e de Integração**: Ao adicionar funcionalidades, certifique-se de incluir testes para cobrir os casos de uso.
- **Execução de Testes**: Garanta que todos os testes passem antes de enviar uma Pull Request:
  ```bash
  ./mvnw test
  ```

---

### 🛠️ Enviando uma Pull Request (PR)
1. Faça o **push** da sua branch:
   ```bash
   git push origin minha-contribuicao
   ```
   
3. Acesse o repositório principal e clique em **New Pull Request**.
4. Descreva as mudanças feitas e associe a PR com a Issue correspondente, se aplicável.
5. Adicione labels apropriadas para categorizar a PR (ex.: `🚀 Enhancement`, `🐞 Bug Fix`).

---

### 🎨 Labels

Para organizar Issues e Pull Requests, use as labels:

- `🐞 Bug`: Relacionado a problemas no código.
- `🚀 Feature Request`: Solicitações de novas funcionalidades.
- `📝 Documentation`: Relacionado à documentação do projeto.
- `🧩 Enhancement`: Melhorias incrementais.
- `🔧 Maintenance`: Tarefas de manutenção do projeto.
- `🔍 Review`: PRs aguardando revisão.

---

### 💬 Código de Conduta

Ao participar deste projeto, você concorda em seguir nosso [Código de Conduta](./CODE_OF_CONDUCT.md). Mantenha uma comunicação respeitosa e colaborativa.

---

### 📞 Contato

Para dúvidas sobre o processo de contribuição, entre em contato via Issues ou diretamente com os mantenedores do projeto.

Agradecemos sua colaboração para o `mf-auth` e por contribuir para a excelência de nossa equipe! 😊

