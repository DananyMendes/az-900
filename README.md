# Guia: Criando uma Subscrição, Grupo de Recursos e Azure Data Factory no Azure

## 📌 Pré-requisitos

- Conta Microsoft (Outlook, Hotmail, etc.)
- Acesso ao portal do Azure: [https://portal.azure.com](https://portal.azure.com)

---

## 🔑 1. Criando uma Subscrição no Azure

> Caso já tenha uma subscrição, você pode pular esta etapa.

1. Acesse o portal do Azure: [https://portal.azure.com](https://portal.azure.com)
2. No menu lateral, clique em **"Subscrições"** (Subscriptions).
3. Clique em **"+ Adquirir uma Subscrição"**.
4. Escolha um tipo de plano:
   - Gratuito (Free Trial) ou
   - Pay-As-You-Go (Pagamento conforme o uso)
5. Siga os passos para:
   - Verificar identidade
   - Informar forma de pagamento
   - Aceitar os termos

---

## 📦 2. Criando um Grupo de Recursos

1. No portal do Azure, pesquise por **"Grupos de recursos"**.
2. Clique em **"+ Criar"**.
3. Preencha os campos:
   - **Subscrição**: selecione a subscrição desejada
   - **Nome do grupo de recursos**: ex: `rg-datafactory`
   - **Região**: escolha a região mais próxima dos seus usuários ou serviços
4. Clique em **"Revisar + criar"** e depois em **"Criar"**.

---

## 🏭 3. Criando um Azure Data Factory

1. No portal do Azure, pesquise por **"Data Factory"**.
2. Clique em **"+ Criar"**.
3. Na aba **"Informações básicas"**, preencha:
   - **Subscrição**: selecione sua subscrição
   - **Grupo de recursos**: selecione o grupo criado anteriormente
   - **Nome da instância**: ex: `adf-projeto-x`
   - **Região**: escolha a mesma região do grupo de recursos
4. Aba **"Git Configuration"** (opcional): pode deixar desmarcado por enquanto.
5. Clique em **"Revisar + criar"** e depois em **"Criar"**.

---

## ✅ Conclusão

Após seguir esses passos, você terá:

- Uma subscrição ativa no Azure
- Um grupo de recursos configurado
- Um ambiente Azure Data Factory pronto para uso

> Agora você pode começar a criar pipelines, datasets e integrações com outros serviços como Data Lake, SQL, APIs etc.
