# Criação de Grupos de Recursos no Azure

## O que é um Grupo de Recursos?

Um **Grupo de Recursos** no Azure é um container lógico que mantém recursos relacionados para uma solução Azure. Ele facilita o gerenciamento, monitoramento, e controle de custos dos recursos.

## Comandos Básicos para Criar um Grupo de Recursos

### 1. Usando o Portal do Azure

1. Acesse o [Portal do Azure](https://portal.azure.com).
2. No menu lateral, clique em **Grupos de Recursos**.
3. Clique no botão **Adicionar**.
4. Preencha os seguintes campos:
   - **Nome do Grupo de Recursos**: Nome que identifica o grupo.
   - **Região**: A localização geográfica onde o grupo será hospedado.
5. Clique em **Revisar + Criar** e depois em **Criar**.

### 2. Usando o Azure CLI

Você pode criar um grupo de recursos no Azure usando o Azure CLI. Siga o comando abaixo:

```bash
az group create --name NomeDoGrupo --location "Região"
```

### Considerações
- **Localização**: Escolha a localização (região) dos seus grupos de recursos com base na proximidade dos usuários finais ou outros requisitos de conformidade.

- **Políticas de Governança**: Utilize o Azure Policy para aplicar políticas específicas, como restrições de região ou compliance.

- **Orquestração de Infraestrutura**: Combine a criação de grupos de recursos com ferramentas de infraestrutura como código, como Terraform ou ARM Templates, para garantir consistência.

### Conclusão
Criar e gerenciar grupos de recursos no Azure é uma etapa fundamental para organizar, monitorar e otimizar o uso de recursos na nuvem. Seja pelo portal, CLI, ou PowerShell, você pode configurar e controlar seu ambiente com flexibilidade e eficiência.