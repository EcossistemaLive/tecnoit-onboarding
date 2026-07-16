# Changelog - Portal de Onboarding Tecno IT

Este documento registra o histórico de alterações estruturais e de conteúdo realizadas no projeto `tecnoit-onboarding`.

## [16/07/2026] - Incorporação dos decks de Contrato/CLT e SESMT

Conteúdo consolidado a partir das apresentações de onboarding (equipe de escritório/CLT e equipe de campo), mantendo o layout, os design tokens e os componentes existentes.

### Adicionado
- **Modelo Geral · SESMT:** pilares de segurança (Brigada de Emergência, NRs, EPIs), blocos de cultura ("Nosso compromisso" / "Nosso papel"), card de Brigada de Emergência (Goiânia) e ampliação das tags de NR (NR-01, 06, 07, 10, 17, 23, 26, 33, 35). Risco de "Trânsito" incluído.
- **Engenharia · Segurança do Trabalho em Campo:** nova seção com NR-01 (GRO), isolamento e sinalização com cones, NR-06 (EPIs), NR-10 detalhado (desenergização/bloqueio/EPCs), NR-17, NR-23 (incêndios), NR-35 (altura, detalhado) e NR-33 (espaço confinado com AR + PET), além do fluxo "Como agir em incidente/acidente/emergência".
- **RH:** contrato de experiência (45+45 dias), Vale-Transporte (6%), Vale-Refeição/Alimentação (PLUXEE, R$ 756,80), plano de saúde (custeio 50%/30%, adesão 90 dias), seguro de vida, seção de Férias (com tabela por faltas), Faltas Legais e Medicina do Trabalho.
- **Financeiro:** seção de Datas de Pagamento (salário 5º dia útil, 13º em 20/nov e 30/nov, PLR em fevereiro).

### Alterado
- **VR/VA:** passa a ser atribuído ao Cartão PLUXEE (ex-Sodexo); o Caju é reposicionado como cartão de qualidade de vida / benefícios.
- **Atestados:** entrega no 1º dia de retorno, com CID (antes: 48h e CRM).
- **Fluxo de incidentes:** comunicação à liderança, que aciona o SESMT (antes: direto ao SESMT).
- **Ponto eletrônico:** app nomeado como Pontomais (mantendo a geolocalização).
- **Banco de horas:** compensação em até 12 meses; saldo não compensado pago em folha.

### Pendente
- Número de telefone da Medicina do Trabalho (o material de origem trazia um placeholder e não foi publicado).

## [04/05/2026] - Reestruturação Departamental e Assistente Nauta

### Adicionado
- **Nova aba "Supply Chain":** Criada a partir do desmembramento da antiga aba "Administrativo". Foca exclusivamente na cadeia de suprimentos, incluindo:
  - Missão do Supply Chain.
  - Processo de Compra.
  - Gestão de Suprimentos.
  - Logística e Distribuição.
  - Processo de Medição.
  - Processo de Garantia.
  - Solicitação de Pagamento e Política de Compra.
  - Timeline dos Primeiros 30 Dias.
- **Nova aba "🤖 Nauta":** Lançamento do espaço dedicado ao novo assistente virtual da Tecno IT.
  - Inserção de mensagem de boas-vindas e introdução às funcionalidades.
  - Listagem de serviços de autoatendimento via chat (Holerite, RH, Caju, Logística, Compras, Medições, etc.).
  - Acesso rápido a documentos cruciais (Política de Segurança, Viagens, Manuais Caju).
  - Adicionado botão interativo e destacado (Call to Action) para o contato de WhatsApp do Nauta `(62) 9269-0779`.

### Alterado
- **Aba "Adm. Financeiro" renomeada:** Atualizada para "Financeiro", abrigando agora apenas os tópicos relativos a governança, estrutura societária e planejamento econômico.
- **Card da Estação na Navegação Principal:** Onde constava "Estação Administrativa", agora reflete corretamente "Estação Supply Chain — Estrutura e Navegação" com o ícone 📦.
- **Correção de Identidade Visual:** Feito o *revert* de um commit anterior (relacionado a uma suposta atualização de identidade "ViDi") que havia quebrado o layout. O projeto segue os *Design Tokens* estipulados para a Tecno IT / Universo IT.
