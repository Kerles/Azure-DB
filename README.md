<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=vimeo" alt="DIO - Project"></a>
<a href="https://en.wikipedia.org/wiki/Artificial_intelligence"><img src="https://img.shields.io/badge/AI-Project-FED564?logo=openai" alt="AI - Project"></a>
<a href="https://portal.azure.com/" title="Vá para a página inicial do Portal"><img src="https://custom-icon-badges.demolab.com/badge/Microsoft%20Azure-0089D6?logo=msazure&logoColor=white)](#)"></a>
<a href="https://www.sublimetext.com/" title="Vá para a página inicial do Editor"><img src="https://img.shields.io/badge/Sublime%20Text-%23575757.svg?logo=sublime-text&logoColor=important"></a>


# Configurando uma instância de Banco de Dados no Azure

Este repositório  contém resumos, anotações e dicas práticas sobre o processo de criação de um cluster do Azure Cosmos DB for PostgreSQL, desde a definição dos detalhes do projeto até a configuração dos recursos de escalabilidade, escolha da versão do PostgreSQL, definição do nome do banco de dados e configuração da conta de administrador.



### Provisionamento de Recursos

1. **Acesso ao Portal Azure:**  
   - Acessei o [portal.azure.com](https://portal.azure.com) e fiz login na minha conta.

2. **Criação de Recursos:**  
     - Passei o mouse sobre Azure Cosmos DB porque já tinha selecionado antes na seção banco de dados em Criar um recurso.
     - Cliquei em Criar e seguir  para o processo de configuração.
 
3. **Detalhes do Projeto:**
     - Selecionei  a assinatura e o grupo de recursos.
     - Testei definir um nome para o cluster
      Selecionei a região: (US) East US.
     
   
4. **Scale:**
     - Selecionei o Número de nós no cluster, a quantidade de vCore e RAM e a estimativa de custo por mês.

5. **PostgreSQL Version**
   - Escolhir a versão 16 do PostgreSQL 

6. **Conta de Administrador:**
   - Definir o nome de usuário para a conta administrativa.
   - Gerei uma senha segura e guardei.
   
7. **Revisão:**
   - Depois de Revisar todas caixas de seleções e informações configurada.
   - Cliquei em "Criar" para provisionar o serviço.

## ⚡ Dicas de Performance e Escalabilidade

- **Monitoramento:**  
Se preciso  monitora o desempenho dos meus recursos utilizo o Azure Monitor e o Log Analytics. Posso configurar alertas para identificar e agir sobre picos de uso ou problemas de performance.

- **Escalabilidade:**  
Posso usar a escalabilidade tanto vertical quanto horizontal para garantir que a minha infraestrutura acompanhe o crescimento da aplicação.

- **Pools de Conexão:**  
Em bancos de dados, posso configura pools de conexão para uma gestão eficiente das conexões simultâneas e para gerir melhor os recursos.


## 💰 Otimização de Custos

- **Ajuste Dinâmico dos Recursos:**  
Posso reduzir a escala dos recursos durante horários de menor uso para evitar custos desnecessários.
  
- **Reservas:**  
 Quando o uso for contínuo e de longo prazo, considero adquirir reservas para obter descontos em relação ao modelo de pagamento por uso.


- **Ambientes de Teste:**  
  Posso utiliza serviços em tiers básicos ou de teste em ambientes de desenvolvimento, garantindo assim o equilíbrio entre custo e performance.


## 🛡️ Segurança e Conformidade

- **Regras de Firewall e Redes Virtuais:**  
Posso configurar as regras para permitir somente IPs e redes confiáveis.
- **Identity Management:**  
Posso utiliza a autenticação via Azure Active Directory (Azure AD) para gerenciar acessos e permissões de forma centralizada.

- **Audit Logs:**  
  Habilitei a auditoria e o monitoramento de logs para acompanhar os acessos e as alterações nos meus recursos.

## 🔄 Migração e Integração

- **Azure Database Migration Service:**  
Essa ferramenta pode me ajuda a realizar a migração de forma rápida e com o mínimo de downtime, garantindo que a migração seja transparente para os usuários e sem interrupções significativas no serviço. 

- **Data Migration Assistant:**  
 Posso verifica a compatibilidade e preparar  meu ambiente para a migração utilizado  essa ferramenta.

- **Integração com Serviços Azure:**  
  Posso  utiliza  serviços do Azure como App Services, Functions e Logic Apps que podem ser integrados para construir soluções completas.

## 📚 Conclusão

Eu utilizei o cluster do Azure Cosmos DB for PostgreSQL no Azure de exemplo mesmo não tendo assinatura ativamente, criando um repositório com resumos, anotações e dicas sobre o processo. Essa experiência me permitiu explorar desde o provisionamento dos recursos até práticas de escalabilidade, otimização e segurança, proporcionando um guia claro e funcional para quem deseja aprender sobre a configuração de bancos de dados na plataforma Microsoft Azure.
