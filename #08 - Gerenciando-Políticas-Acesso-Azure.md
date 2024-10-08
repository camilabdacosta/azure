# Gerenciando Políticas | Azure

## 1. Portal de Confiança do Azure

O **Portal de Confiança do Azure** oferece visibilidade e controle sobre a conformidade e segurança dos seus recursos no Azure. Ele proporciona informações sobre práticas recomendadas, normas de conformidade e segurança de dados.

### Como acessar e utilizar o Portal de Confiança:

1. **Acesse o Portal de Confiança**:
   - O portal facilita a gestão de políticas de conformidade e ajuda a garantir que os recursos estejam em conformidade com as melhores práticas de segurança e exigências regulatórias.
   - Inclui uma visão geral das certificações e do cumprimento de normas do Azure.

---

## 2. Preview do Azure

O **Preview do Azure** permite experimentar novos serviços e funcionalidades antes do lançamento oficial.

### Como ativar um recurso em Preview:

1. **Acesse o Portal do Azure**:
   - Faça login no [Portal do Azure](https://portal.azure.com/).

2. **Navegue para 'Todos os serviços'**:
   - No menu de navegação à esquerda, selecione **"Todos os serviços"** e procure por recursos em Preview.

3. **Selecione e ative o Preview**:
   - Escolha o recurso desejado e siga as instruções para ativá-lo.
   - Lembre-se de que recursos em Preview podem ter funcionalidades limitadas.

---

## 3. Bloqueio de Recursos

O **Bloqueio de Recursos no Azure** protege recursos críticos contra exclusão ou modificação acidental.

### Como configurar um bloqueio de recurso:

1. **Acesse o Portal do Azure**:
   - Faça login no [Portal do Azure](https://portal.azure.com/).

2. **Navegue até o recurso**:
   - Selecione **"Recursos"** no menu de navegação à esquerda e escolha o recurso que deseja proteger.

3. **Configure o bloqueio**:
   - No painel do recurso, selecione **"Bloqueios"**, clique em **"Adicionar bloqueio"**, e escolha:
     - **ReadOnly**: Apenas leitura permitida.
     - **CanNotDelete**: Impede a exclusão do recurso.

4. **Defina nome e descrição**:
   - Insira o nome e a descrição do bloqueio e clique em **"Salvar"**.

---

## 4. Gerenciamento de Policies

O **gerenciamento de políticas no Azure** assegura que seus recursos estejam em conformidade com as normas da sua organização.

### Como criar e aplicar uma política:

1. **Acesse o Portal do Azure**:
   - Faça login no [Portal do Azure](https://portal.azure.com/).

2. **Navegue para 'Azure Policy'**:
   - Selecione **"Azure Policy"** no menu de navegação à esquerda.

3. **Crie uma nova política**:
   - Selecione **"Definitions"**, clique em **"New Policy Definition"**, e defina os critérios da política.

4. **Aplique a política**:
   - Após definir a política, selecione **"Assignments"** e clique em **"Assign Policy"**.
   - Escolha a política criada e defina o escopo de aplicação.

5. **Revise e salve**:
   - Revise os detalhes e clique em **"Create"** para aplicar a política.
