🏭 Inventory Flow Manager

Plataforma desktop para controle inteligente de estoque com integração direta ao processo de produção.

🧩 Visão Geral

O Inventory Flow Manager é uma aplicação desenvolvida em Python com foco na gestão eficiente de materiais e produtos em ambientes de montagem.

Diferente de sistemas tradicionais, este projeto implementa um modelo onde o estoque não é apenas armazenado — ele interage diretamente com a produção, garantindo consistência automática entre insumos e produtos finais.

A aplicação foi projetada para uso administrativo, com uma interface simples, responsiva e orientada a ações rápidas.

⚙️ Funcionamento do Sistema

O sistema opera com base em três pilares principais:

📥 Entrada de Insumos

Registro e atualização de peças individuais no estoque.

🏗️ Processo de Produção

Criação de produtos finais a partir de um conjunto pré-definido de componentes.

🔄 Sincronização Automática

Ao produzir um item:

O sistema valida a disponibilidade de peças
Realiza a baixa automática dos insumos
Atualiza o estoque de produtos finalizados
Persiste todas as operações no banco de dados
🚀 Recursos Disponíveis
🔐 Autenticação restrita para administradores
📦 Gerenciamento completo de peças (CRUD)
🏭 Execução de produção com validação de estoque
📊 Painel com visão geral do inventário
💾 Persistência de dados com banco relacional
🧠 Lógica de vínculo entre peças e produtos
🧠 Diferencial Técnico

O núcleo do sistema é baseado em uma abordagem de composição de produto, onde cada item final depende de múltiplos componentes.

Esse modelo permite simular conceitos utilizados em sistemas industriais reais, como:

Planejamento de necessidade de materiais (MRP)
Controle de consumo de insumos
Automatização de processos operacionais
🛠️ Stack Tecnológica
Camada	Tecnologia
Linguagem	Python 3
Interface	Tkinter / CustomTkinter
Banco de Dados	MySQL / SQLite
Integração DB	mysql-connector-python
🗄️ Estrutura de Dados (Resumo)
Peças: itens base do sistema
Produtos: itens finais produzidos
Relação Produto-Peça: define composição
Usuários: controle de acesso
📈 Próximas Evoluções
📄 Geração de relatórios (PDF / Excel)
📉 Histórico de movimentações
🔔 Alertas de estoque mínimo
📊 Indicadores de produção
🎯 Objetivo do Projeto

Este sistema foi desenvolvido com fins acadêmicos e tem como objetivo aplicar conceitos como:

Modelagem de dados
Regras de negócio
Integração com banco de dados
Desenvolvimento de interfaces desktop
Simulação de cenários reais de produção
📌 Observações

Projeto em constante evolução, com foco em aprendizado prático e melhoria contínua da arquitetura e das funcionalidades.



