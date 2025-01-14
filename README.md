# 📊 Análise e Clusterização de Vendas no Varejo

Bem-vindo ao repositório **Análise e Clusterização de Vendas no Varejo**! Este projeto combina a análise de dados, higienização e clusterização para oferecer insights estratégicos sobre as operações de vendas de uma empresa varejista. O repositório contém scripts de tratamento de dados, clusterização e um dashboard interativo em Power BI.

---

## 🗂️ Estrutura do Repositório

- **`bases/`**: Bases de dados brutas utilizadas no projeto.
- **`Treated_Files/`**: Bases tratadas e preparadas para análise.
- **`icons/`**: Ícones utilizados na criação do dashboard no Power BI.
- **`capturas/`**: Espaço reservado para capturas de tela do dashboard e da clusterização.
- **`Dashboard_vendas.pbix`**: Arquivo do Power BI com as visualizações e análises de vendas.
- **`script`**: Script detalhado contendo as etapas de tratamento, análise e clusterização.
    
---

## 🚀 Funcionalidades

1. **Tratamento de Dados**:
   - Consolidação de múltiplas bases de dados.
   - Higienização e organização para facilitar as análises.
   - Exportação das bases tratadas para uso em diferentes ferramentas.

2. **Clusterização**:
   - Aplicação de algoritmos de clusterização (K-Means) para segmentar clientes com base em:
     - Recência (tempo desde a última compra).
     - Frequência (número de compras realizadas).
     - Valor Monetário (gasto total).
   - Geração de insights para estratégias direcionadas.

--- 

<div align="center">
 <img src="https://github.com/dsilvaphy/analise-e-clusterizacao-vendas-varejo/blob/main/capturas/cluster.png" width="400" height="400">
  </div>

  --- 


3. **Dashboard em Power BI**:
   - Visualização interativa de vendas por cliente, produto e vendedor.
   - Análise de desempenho versus metas.
   - Projeções futuras de faturamento.

---

<div align="center">
    <img src="https://github.com/dsilvaphy/analise-e-clusterizacao-vendas-varejo/blob/main/capturas/dashboard1.png" width="700" height="400">
</div>

---

## 🛠️ Como Usar

1. **Clone o Repositório**:
2. 
   ```bash
   git clone https://github.com/seu-usuario/analise-clusterizacao-vendas.git
   cd analise-clusterizacao-vendas
   ```
3. Instale as Dependências: Certifique-se de ter Python 3.x instalado e as seguintes bibliotecas:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Execute o Script: Navegue até o diretório do script e execute:
   
   ```bash
   python script.py
   ```

## 💡 Insights do Projeto
Este projeto demonstrou como combinar ferramentas analíticas e de visualização para gerar insights estratégicos. Com base nos resultados obtidos:

- Cluster 0: Clientes altamente engajados e de alto valor.
- Cluster 1: Clientes moderadamente ativos, com potencial de engajamento.
- Cluster 2: Clientes ativos com frequência de compra significativa.

## 📄 Licença

Este projeto está licenciado sob a **Creative Commons Attribution-NonCommercial 4.0 International License**. Não é permitido usar o código para fins comerciais.

Veja a licença completa [CC BY-NC 4.0](/creativecommons.org/licenses/by-nc/4.0/deed.pt-br).
