# SGL: Sistema de Gestão de Leituras e Impressão Simultânea

O SGL é um sistema produzido pela própria CEMIG cujo objetivo é a leitura e impressão da fatura, em campo, dos 8.5 milhões de consumidores cativos de baixa tensão da Cemig D.

A solução SGL é constituída de vários módulos, descritos a seguir:


> **SGL Batch** 
Módulo responsável pela troca e tratamento de dados entre o SGL e o CCS. Através desse módulos, todas as informações necessárias às atividades de leitura "descem" do CCS para os coletores e todas as informações de leitura e faturamento "sobem" dos coletores para o SGL.
[Documentação Completa...](SGLBatch)


> **SGL Empreiteira**
Módulo Web utilizado pelas empreiteiras para gestão das atividades de leitura em campo. Através desse módulo a empreiteira realiza a gestão das equipes, distribuição e monitoramento das atividades, além do monitoramento e validação das informações coletadas. 
[Documentação Completa...](SGLEmpreiteira)


> **SGL Cemig**
Módulo Web utilizado por profissionais da Cemig. Através desse módulo é feita a gestão dos contratos, atividades e pagamentos.
[Documentação Completa...](SGLCemig)


> **SGL Coletor**
App instalada nos smartphones utilizados pelos leituristas para leitura e impressão simultânea. A partir desse aplicativo, o leiturista é capaz de carregar os arquivos para realização das atividades em campo, executar atividades, imprimir faturas pela impressora portátil e descarregar os arquivos com informações coletadas/calculadas ao longo do dia.
[Documentação Completa...](SGLColetor)


---


## UML: Como os módulos interagem...

![Minion](\out\UML\uml.png)


## Tables

| Mudança | Descrição | Data Abertura| Status |
| ------ | ----------- | ---------| ------|
| C23453   | Refere-se à inclusão de algumas novas funcionalidades do coletor. As documentos específicos dessa mudança encontram-se disponíveis em [C23453](C23453). O manual do usuário, documento geral do projeto também precisou ser alterado | 12/abril/19| Fechada
| C23497   | Alteração apenas do tamanho do campo da nota estática no coletor. Os documentos da mudança estão disponíveis em [C23497](C23497). Os documentos funcionais e manual do projeto não sofreram alterações| 14/outubro/19| Em construção

