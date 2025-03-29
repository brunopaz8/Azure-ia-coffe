# Azure-ia-coffe

## Ferramentas Utilizadas 🛠️
- **Azure AI Search** - Para criar e consultar índices de busca.
- **Azure AI Services** - Para enriquecer os dados indexados.
- **Azure Blob Storage** - Para armazenar documentos brutos.
- **Azure Portal** - Para gerenciar os serviços e configurações.
- **Search Explorer** - Para testar consultas diretamente no Azure AI Search.

---

## Consultar os Dados Indexados 📁
1. No **Azure AI Search**, acesse **Search Explorer**.
2. Execute buscas básicas:
   ```json
   {
       "search": "*",
       "count": true
   }
   ```
3. Filtre por local:
   ```json
   {
       "search": "locations:'New York'",
       "count": true
   }
   ```
4. Filtre por sentimento negativo:
   ```json
   {
       "search": "sentiment:'negative'",
       "count": true
   }
   ```

---

## Insights e Possibilidades 💡
- **Pesquisa Inteligente:** Melhor organização e recuperação de informações relevantes.
- **Análise de Sentimento:** Entendimento da percepção dos usuários em relação a produtos e serviços.
- **Organização de Documentos:** Permite classificação automática por conteúdo, tags e palavras-chave.
- **Integração com Outras Ferramentas:** Pode ser usado em aplicações web, chatbots, análise de dados e assistentes virtuais.

---

## Aprendizados Adquiridos 💭
- **Configurar e gerenciar recursos do Azure**
- **Indexar e enriquecer dados de forma automatizada**
- **Executar consultas estruturadas para buscar informações**

---





