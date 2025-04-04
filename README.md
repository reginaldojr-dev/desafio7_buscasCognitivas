# ⚙️ Azure Cognitive Search: Indexação e Consulta de Dados com AI

Este repositório faz parte do **Desafio #07 da Bootcamp Decola Tech 2025** e explora o uso do **Azure Cognitive Search** para indexar e consultar dados de forma eficiente.

---

## 🔍 Índice
1. [Sobre o Projeto](#sobre-o-projeto)
2. [Tecnologias Utilizadas](#tecnologias-utilizadas)
3. [Configuração e Uso](#configuração-e-uso)
4. [Insights e Benefícios](#insights-e-beneficios)
5. [Conclusão](#conclusao)

---

## 🚀 Sobre o Projeto
Este projeto aplica técnicas de **organização de documentos e pesquisa eficiente** no **Azure Cognitive Search**, utilizando três etapas principais:
1. **Ingestão de dados**
2. **Criação de índices**
3. **Consulta e extração de insights**

Essa abordagem possibilita uma exploração avançada de documentos, trazendo maior inteligência para buscas e análises.

---

## 🛠️ Tecnologias Utilizadas
- [Azure Cognitive Search](https://azure.microsoft.com/pt-br/products/search/)
- [Azure Blob Storage](https://azure.microsoft.com/pt-br/products/storage/blobs/)
- [Azure Portal](https://portal.azure.com/)
- [API REST/SDK do Azure](https://learn.microsoft.com/en-us/azure/search/search-api-overview)

---

## ▶️ Configuração e Uso
### ✨ 1. Configuração do Azure Cognitive Search
1. Acesse o **[Portal do Azure](https://portal.azure.com/)** e faça login.
2. Crie um **recurso Azure Cognitive Search**.
3. Defina:
   - **Nome do serviço**
   - **Grupo de recursos**
   - **Localização** (Recomenda-se *East US*)
   - **Plano de preço** (*Free* para testes, *Standard* para produção)
4. Clique em **Revisar + Criar** e finalize a criação.

### 📁 2. Configuração do Armazenamento de Dados
1. No **Portal do Azure**, crie uma **Storage Account**.
2. Defina:
   - Nome do armazenamento
   - Localização: *East US*
   - Desempenho: *Standard*
   - Redundância: *LRS*
3. No menu lateral, acesse **Contêineres** e crie um novo contêiner.
4. Configure as permissões e carregue os arquivos a serem indexados.

### 🔎 3. Indexação e Pesquisa
1. No **Azure Cognitive Search**, clique em **Importar Dados**.
2. Escolha **Armazenamento Blob** como fonte de dados.
3. Configure a conexão com a conta de armazenamento.
4. Selecione os arquivos a serem indexados.
5. No **Gerenciador de Pesquisa**, realize consultas utilizando palavras-chave.

---

## 🌟 Insights e Benefícios
- **🔄 Análise Semântica:** melhora a precisão das pesquisas.
- **🎨 Sugestões Inteligentes:** autocomplete e busca preditiva.
- **🎯 Relevância Personalizada:** ranking de resultados ajustável.
- **🌐 Integração Fácil:** compatível com sistemas web e mobile.

### 🔧 Aplicabilidades
- **E-commerce**: busca avançada de produtos.
- **Sistemas de Suporte**: pesquisas inteligentes em FAQs.
- **Análise de Documentos**: indexação de relatórios e artigos.
- **Pesquisa Acadêmica**: mineração de conhecimento.

---

## 📚 Conclusão
Este projeto demonstrou como o **Azure Cognitive Search** pode ser usado para indexação e pesquisa de dados de forma eficiente. Ele é aplicável a diversos cenários, desde buscas empresariais até análise avançada de documentos.

---

## 📝 Nota
Este projeto é parte do **Desafio #07 da Bootcamp Decola Tech 2025** e tem propósitos educacionais, sem afiliação oficial com a Avanade, DIO ou Microsoft.

## 📢 Autor

Projeto desenvolvido por Reginaldo Goulart. Se tiver dúvidas ou sugestões, entre em contato! 😊