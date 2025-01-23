# **Automação de Indicadores**

![Automação de Processos](imagem/capa.png) <!-- Substitua por uma imagem ou banner do projeto, se preferir -->

## **Descrição do Projeto**

Este projeto foi desenvolvido como um exemplo prático de automação de processos corporativos, integrando manipulação de dados, geração de relatórios e envio automatizado de e-mails. Ele simula um ambiente de análise de dados em uma rede de lojas de roupas, com 25 unidades espalhadas pelo Brasil, destacando a eficiência e a precisão no tratamento e distribuição de informações estratégicas.

## **Funcionalidades**

- **Coleta e Processamento de Dados**:
  - Consolidar dados de diferentes fontes: Excel e CSV.
  - Realizar cálculos para indicadores-chave de desempenho (KPIs) diários e anuais.

- **Geração de Relatórios OnePage**:
  - Criar relatórios resumidos para cada loja com indicadores relevantes, metas e sinalizações (verde/vermelho) para facilitar a análise.

- **Envio Automatizado de E-mails**:
  - Gerentes de loja recebem seus respectivos relatórios e dados de vendas diários.
  - A diretoria recebe um e-mail consolidado com rankings de faturamento (diário e anual), além de destaques da melhor e pior loja.

- **Backup e Histórico**:
  - Os relatórios diários são salvos em pastas específicas, criando um histórico organizado por data.

---

## **Tecnologias Utilizadas**

- **Python**:
  - `pandas`-  Manipulação de dados.
  - `win32com.client`- Automação de envio de e-mails.
  - `openpyxl`- Tratamento de arquivos Excel.
  - `pathlib` - Manipulação de caminhos de arquivos.
- **Excel/CSV**: Entrada de dados e armazenamento.
- **Jupyter Notebook**: Desenvolvimento e execução interativa do código.

---

## **Habilidades Demonstradas**

Este projeto reflete competências importantes, como:

- **Automação e Eficiência**: Uso de Python para eliminar tarefas manuais repetitivas.
- **Manipulação Avançada de Dados**: Processamento, cálculo e organização de grandes volumes de informações.
- **Comunicação Clara**: Geração de relatórios visualmente organizados e envio de e-mails automatizados.
- **Organização de Projetos**: Estruturação do código, backups e documentação clara.
- **Foco em Resultados**: Apresentação de insights relevantes para tomada de decisões estratégicas.

---

## **Como Utilizar o Projeto**
1. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/seu-usuario/automacao-indicadores.git
   cd automacao-indicadores

### **Pré-Requisitos**

- **Python 3.10+**
- **Bibliotecas Necessárias**:
  - `pandas`
  - `openpyxl`
  - `win32com.client`

Para instalar as dependências, execute o comando abaixo no terminal:

```bash
pip install pandas openpyxl pywin32

### **Estrutura do Projeto**

📂 automacao-indicadores/
├── 📄 README.md                     # Arquivo de descrição do projeto
├── 📄 Apresentacao.md              # Explicação detalhada do projeto
├── 📂 Backup Arquivos Lojas/       # Pastas para backup de relatórios diários
    ├── 📂Bourbon Shopping SP
        ├──📄 Emails.xlsx           # relatório de vendas do dia anterior
├── 📂 Base de Dados/
    ├── 📄 Emails.xlsx              # Informações dos gerentes e diretoria
    ├── 📄 Vendas.xlsx              # Dados de vendas por loja
    ├── 📄 Lojas.csv                # Lista de lojas         
├── 📄 Automacao_Indicadores.ipynb # Código principal


