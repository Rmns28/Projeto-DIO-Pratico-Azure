# Projeto-Pr-tico-Azure
# Projeto Prático - Criando e Monitorando Recursos no Azure com Conta Gratuita Estudante

## Objetivo do Projeto

Esse projeto tem como objetivo mostrar, de forma prática e fácil de entender, como criar e organizar recursos no Microsoft Azure, usando uma conta gratuita de estudante.

Aqui você vai ver como:
- Criar recursos no Azure
- Organizar tudo com boas práticas
- Controlar e monitorar os gastos
- Usar automação com Cloud Shell
- Criar templates de infraestrutura (ARM Templates)

---

## Passo a Passo do Projeto

### 1. Criação da Conta Gratuita de Estudante
Acesse: https://azure.microsoft.com/pt-br/free/students/



---

### 2. Criando Grupo de Recursos
- Pesquise por "Grupos de Recursos"
- Clique em "Criar"
- Nome sugerido: `rg-projeto-dio`
- Escolha a região


---

### 3. Criando o Azure Data Factory
- Pesquise por "Data Factory"
- Clique em "Criar"
- Nome: `adf-projeto-dio`
- Grupo de recursos: `rg-projeto-dio`


---

### 4. Dashboard Personalizado
Monte um painel com os principais recursos do projeto.



---

### 5. Monitorando Custos
- Pesquise por "Custo e Cobrança"
- Crie alertas de gasto
- Visualize gráficos



---

### 6. Automação com Cloud Shell
Execute comandos diretamente no navegador usando o Cloud Shell.

Exemplo:

```bash
az group list
```



---

### 7. Criando ARM Templates
Facilite a criação automática de recursos usando templates.

Exemplo:

```json
{
  "$schema": "https://schema.management.azure.com/schemas/2019-04-01/deploymentTemplate.json#",
  "contentVersion": "1.0.0.0",
  "resources": []
}
```



---

## O que eu aprendi com esse projeto?
- Criação de recursos no Azure
- Organização com grupos de recursos
- Controle de custos e alertas
- Automatização com Cloud Shell
- Infraestrutura como código (IaC)
- Boas práticas de nomeação
- Como montar dashboards personalizados

---

## Possibilidades Futuras
- Criar automações mais avançadas
- Integrar o Data Factory com bancos de dados
- Criar políticas de governança no Azure
- Aprender sobre DevOps no Azure
