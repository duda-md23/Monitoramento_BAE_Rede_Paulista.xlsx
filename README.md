📊 Sistema de Monitoramento BAE (Planilha)
A planilha de monitoramento da Busca Ativa Escolar (BAE) foi estruturada sob as diretrizes da Secretaria de Educação e Esportes (SEPA) de Paulista/PE. Ela foi desenhada para ser simples, visual e centralizada, ajudando a combater a evasão escolar na rede.

Organização Técnica
Total de Abas: 62 abas (1 Aba SUMÁRIO + 61 abas de escolas).
Aba SUMÁRIO: Funciona como um painel de controle central. Traz indicadores consolidados da rede (via fórmulas automáticas como =COUNTA) e uma lista de todas as escolas com seus respectivos Códigos MEC, telefones e e-mails institucionais @edu.
Navegação Dinâmica: Cada escola possui um botão de acesso rápido gerado pela fórmula =HYPERLINK, que direciona o usuário instantaneamente para a aba específica da escola com um clique.
Abas Individuais (Escolas): Cada escola possui sua própria planilha de acompanhamento (ex: 26188759 - EDNA MARINHO DA SI) com cabeçalhos elegantes em verde-esmeralda e um painel local de KPIs (estudantes registrados, alunos sob monitoramento BAE e faltas por motivos de saúde).
Regras de Entrada e Validação de Dados
Para evitar erros ortográficos que quebrem as contagens estatísticas, as colunas de digitação manual foram destacadas em verde-claro suave e contam com menus suspensos nativos (Validação de Dados por Dropdown):

Benefícios Sociais (Bolsa Família): Dropdown de SIM / NÃO.
Mês do Registro: Seleção rápida de JANEIRO a DEZEMBRO.
Motivo da Infrequência: doença, Questões de saúde, Evasão escolar, Mudança de domicílio, Dificuldade de acesso/transporte, Outros.
Meio de Contato: PESSOALMENTE, TELEFONE, WHATSAPP, VISITA DOMICILIAR, OUTRO.
Status Atual da Situação: FREQUENTE, INFREQUENTE, EVADIDO, TRANSFERIDO, NÃO LOCALIZADO.
Nota de Simplificação: Esta planilha foi desenvolvida de forma 100% independente do sistema estadual SIEPE e sem campos do programa Pé-de-Meia, otimizando o fluxo de trabalho e focando unicamente no controle local dos monitores da Busca Ativa.

🛠️ Dica de Manutenção: Adicionar Colunas em Massa (Agrupamento de Abas)
Se houver a necessidade de adicionar novas informações a todas as 61 escolas simultaneamente (como a inclusão da coluna "NOME DO ESTUDANTE"), você pode utilizar o recurso de Agrupamento de Planilhas do Excel para fazer a alteração em uma única aba e replicar automaticamente para as demais de uma só vez:

Abra o arquivo no Microsoft Excel ou Google Sheets.
Selecione e Agrupe as Abas:
Clique com o botão direito do mouse sobre qualquer aba de escola na barra inferior.
Escolha a opção "Selecionar Todas as Planilhas" (as abas ficarão com fundo branco destacado).
Atenção: Segure a tecla Ctrl (no Windows) ou Cmd (no Mac) e clique sobre a aba SUMÁRIO para desmarcá-la. Não queremos alterar o painel de controle principal!
Insira a Nova Coluna:
Clique com o botão direito do mouse em cima da letra da coluna onde deseja fazer a inserção (ex: clique na letra F correspondente a "ANO/SÉRIE...").
Selecione "Inserir". Uma nova coluna vazia será criada na mesma posição em todas as 61 escolas.
Dê Nome ao Cabeçalho:
Escreva o título desejado (ex: "NOME DO ESTUDANTE") no cabeçalho da nova coluna.
Desagrupe as Abas (MUITO IMPORTANTE):
Clique novamente com o botão direito sobre qualquer aba na parte inferior e selecione "Desagrupar Planilhas".
Aviso: Se você esquecer de desagrupar, qualquer dado que digitar em uma das escolas será copiado exatamente igual para todas as outras 60!
