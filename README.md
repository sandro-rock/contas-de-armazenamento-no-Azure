# contas-de-armazenamento-no-Azure

Criando Contas de Armazenamento no Microsoft Azure
As contas de armazenamento no Azure são usadas para armazenar objetos como blobs, arquivos, filas e tabelas. A seguir está um guia resumido para a criação de uma conta de armazenamento no Azure:

Acessar o Portal do Azure

Acesse o portal do Azure (portal.azure.com) e faça login na sua conta.
Iniciar o Processo de Criação

No painel principal, clique em "Criar um recurso" e, em seguida, pesquise por "Conta de Armazenamento".
Clique em "Criar" para iniciar o processo.
Configurar as Informações Básicas

Escolha a assinatura e o grupo de recursos onde a conta de armazenamento será criada. Você pode selecionar um grupo existente ou criar um novo.
Defina um nome exclusivo para a conta de armazenamento.
Selecione a região em que deseja criar a conta. Escolha uma região próxima aos seus usuários para reduzir a latência.
Escolha o desempenho (Standard ou Premium), onde Standard é ideal para a maioria dos casos e Premium oferece maior desempenho.
Defina o modelo de redundância:
LRS (Locally Redundant Storage): armazena cópias dentro de uma única região.
GRS (Geo-Redundant Storage): armazena cópias em duas regiões geograficamente distantes.
ZRS (Zone-Redundant Storage): armazena cópias em diferentes zonas de uma mesma região.
Configurações Avançadas

Configure opções como acesso ao ponto final (público ou privado) e política de criptografia (gerenciamento de chaves).
Escolha o tipo de conta de armazenamento:
General-purpose v2: oferece suporte para todos os tipos de armazenamento (Blobs, Arquivos, Tabelas, etc.).
BlobStorage: otimizado apenas para o armazenamento de blobs (arquivos).
Revisar e Criar

Após configurar as opções desejadas, clique em "Revisar + Criar".
Revise as informações para garantir que tudo está correto.
Clique em "Criar" para iniciar o processo de implantação da conta de armazenamento.
Gerenciamento da Conta de Armazenamento

Após a criação, você pode acessar a conta de armazenamento para gerenciar recursos como Blobs, Files, Queues, e Tables.
Esse é o processo básico para criar uma conta de armazenamento no Microsoft Azure.
