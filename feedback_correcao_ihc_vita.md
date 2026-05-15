# Parecer de Correção — Projeto VITA

**Projeto avaliado:** VITA — Visual Intelligence for Trait Analysis  
**Equipe identificada:** Luis Marim e Stella Correia  

## Síntese do parecer

O projeto VITA apresenta uma proposta tecnicamente sofisticada e bem contextualizada: um sistema de apoio à decisão clínica para triagem precoce do TEA com visão computacional, deep learning e explicabilidade por mapas de calor. A documentação mostra maturidade na compreensão do domínio, bom alinhamento entre problema, público-alvo, protótipo e avaliação empírica, além de uma preocupação recorrente com ética, privacidade, confiança e não substituição do profissional.

Os melhores pontos do trabalho estão na caracterização do problema, no cenário de análise, na prototipação, na coleta de dados e na avaliação por observação do usuário. Nessas partes, a equipe conseguiu conectar conceitos de IHC a uma situação real de uso, evitando tratar a interface apenas como um conjunto de telas.

As fragilidades mais relevantes estão nas entregas metodologicamente mais formais: MoLIC, inspeção heurística, análise de tarefas e metas quantitativas de usabilidade. Nessas partes, há bom entendimento do sistema, mas nem sempre o artefato produzido respeita a notação, a granularidade ou os critérios pedidos no enunciado. Como MoLIC e avaliação heurística são itens conceitualmente importantes e de maior impacto avaliativo, essas pendências impedem que o projeto seja considerado plenamente completo.

## Visão consolidada por assunto

| Assunto avaliado | Nível de atendimento | Comentário sintético |
|---|---:|---|
| Conhecimento do problema | **Bom** | O projeto responde à maior parte das questões essenciais, com objetivo, público, funcionalidades, tecnologias e contexto bem definidos. |
| Análise de concorrência | **Parcial** | Há concorrentes e síntese de funcionalidades, mas os prints não estão incorporados no repositório/wiki e a análise de padrões de interface ficou genérica. |
| Personas, empatia, contexto e jornada | **Bom** | Persona primária, contexto e jornada estão bem construídos; faltam autoria individual e maior completude conforme número de integrantes. |
| Cenário de análise/problema | **Muito bom** | Cenário adequado, sem antecipar solução, com atores, título, refinamento e inserções entre colchetes. |
| Análise de tarefas | **Parcial** | Há HTA, GOMS e CTT para os dois membros, mas faltam tabelas auxiliares do HTA e os CTTs não representam concorrência. |
| Prototipação | **Muito bom** | Fluxo, telas, teste com colega, críticas e telas finais estão bem documentados. |
| Coleta de dados | **Bom** | Identifica dados, participantes, ética e três técnicas com instrumentos; poderia materializar melhor os formulários finais. |
| Ciclo de vida de engenharia de usabilidade | **Parcial** | Plataforma e princípios estão bons; metas quantitativas não seguem plenamente os cinco fatores de usabilidade exigidos. |
| Modelo conceitual | **Bom com ajustes** | Cenário de interação, DCC, mapa de objetivos e signos aparecem; faltam mapas individuais e maior cobertura dos signos. |
| MoLIC | **Insuficiente** | O material entregue é um fluxograma genérico, não um diagrama MoLIC conforme a notação esperada. |
| Protótipo final / Figma | **Bom** | As telas finais existem e são suficientes, mesmo sem link Figma. |
| Planejamento da avaliação | **Bom** | O DECIDE está contextualizado e coerente, mas a lista de instrumentos poderia estar mais operacional. |
| Inspeção heurística | **Insuficiente** | Há apenas uma violação, sem print real associado, e não cobre todas as telas nem uma avaliação completa por integrante. |
| Observação do usuário | **Muito bom** | A avaliação empírica é uma das partes mais fortes; há usuários, tarefas, métricas, links, respostas e conclusão. |

## Conhecimento do problema

A equipe apresenta uma boa compreensão do problema ao descrever o VITA como uma ferramenta de apoio à triagem precoce do TEA. O problema é formulado a partir de dois pontos centrais: a subjetividade da avaliação tradicional e o tempo elevado de triagem. Essa formulação é adequada do ponto de vista de IHC, pois parte de uma dificuldade humana e contextual antes de falar da solução tecnológica.

Também há bom atendimento do requisito de funcionalidades. Para uma equipe com dois integrantes, era necessário apresentar pelo menos duas funcionalidades relevantes na visão do usuário. O projeto apresenta mais do que isso: upload e processamento de imagens, score de predição, mapas de calor, análise biométrica regional, relatório explicativo, feedback do especialista e análise temporal. Esse conjunto é suficiente e bem conectado ao objetivo do sistema.

O contexto de uso também está bem caracterizado: clínicas, consultórios, centros de triagem, profissionais de saúde e situações de alta carga cognitiva. Esse ponto é importante porque, em IHC, usabilidade não é uma propriedade abstrata da tela, mas uma relação entre usuários, tarefas, equipamentos e ambiente de uso.

Os pontos que precisam ser corrigidos são de explicitação formal. O documento não marca claramente alguns itens do enunciado, como “Título Original do TCC”, “Previsto desenvolver interface? Sim/Não” e “Qual o produto final?”. Esses elementos aparecem de modo implícito, mas deveriam estar respondidos de forma direta para atender completamente ao modelo original.

**Recomendação:** incluir uma seção objetiva com as perguntas do conhecimento do problema respondidas em formato direto, mantendo a riqueza textual já existente na Wiki.

## Análise de concorrência e padrões de mercado

A análise apresenta concorrentes ou sistemas representativos utilizados por clínicas, como iClinic e Legwork. A escolha pode ser aceita porque o enunciado permite analisar softwares usados pelo público-alvo, não apenas concorrentes idênticos. A equipe também descreve funcionalidades, perfil de uso e aspectos de UX.

O ponto positivo está em reconhecer que o VITA precisa aprender com padrões de sistemas clínicos: simplicidade de uso, fluxo em nuvem, agendamento, relatórios e eficiência operacional. Isso ajuda a equipe a pensar a interface dentro do ecossistema real do usuário.

A principal falha é que os prints das interfaces não estão incorporados diretamente no arquivo da Wiki. O documento informa um link externo para imagens, mas o requisito central era documentar visualmente os padrões, affordances e convenções observáveis. Para fins de correção, um link externo não é tão robusto quanto imagens anexadas ao repositório e comentadas no próprio documento.

A seção de padrões e tendências também ficou genérica. Foram citadas tendências como cloud-first, automação e uso de dados, mas faltou traduzir isso para padrões visuais e interacionais: dashboards clínicos, cards de status, barras de progresso, filtros, tabelas, feedback de carregamento, linguagem visual de alerta, hierarquia de relatórios, acessibilidade para profissionais sob pressão temporal etc.

**Recomendação:** inserir prints no próprio repositório/wiki e, abaixo de cada print, indicar quais padrões serão reaproveitados ou evitados no VITA. A análise deve sair de “o mercado usa cloud” para “interfaces clínicas costumam organizar dados em cards, indicadores de status, prontuário/relatório e fluxos sequenciais; o VITA adotará ou adaptará esses padrões por tais motivos”.

## Personas, mapa de empatia, contexto de uso e jornada

A persona Dra. Helena é bem construída. Ela tem função, contexto social, econômico e cultural, dores, necessidades e relação com tecnologia. O projeto acerta ao tratar a profissional de saúde como uma usuária crítica, exigente, cética quanto a sistemas “caixa-preta” e dependente de confiança, transparência e evidência. Essa abordagem está alinhada à literatura de design centrado no usuário, pois descreve motivações, restrições e expectativas, e não apenas idade ou profissão.

O público-alvo também foi adequadamente caracterizado: neuropediatras, psiquiatras infantis, neuropsicólogos, clínicas multidisciplinares e centros de reabilitação. A equipe ainda apresenta características demográficas, comportamentais, psicográficas e geográficas.

A documentação sobre quais dados o sistema deve guardar é pertinente: imagens, metadados de inferência, mapas de calor, contribuições regionais e feedback do especialista. Esse ponto é especialmente bom porque conecta persona, domínio clínico e requisitos de interação.

O mapa de empatia está bem desenvolvido em texto. A equipe contempla o que a usuária vê, ouve, diz/faz, pensa/sente, dores e ganhos. A jornada também está bem estruturada, começando no gatilho da consulta, passando pelo upload, análise, relatório e feedback. Isso mostra boa continuidade entre persona, tarefa e interface.

As falhas são formais. A equipe tem dois integrantes, mas apresenta apenas uma persona primária sem identificar autoria individual. Pelas regras do projeto, deveria haver uma solução completa por membro ou, no mínimo, explicitar a contribuição de cada integrante. Além disso, a imagem do mapa de empatia está referenciada como `imagens/empatia.png`, mas esse arquivo não foi encontrado no ZIP analisado. Isso sugere link quebrado ou recurso não versionado.

A ausência de persona secundária não deve ser tratada como falha grave, pois as regras priorizam personas primárias. Ainda assim, a própria atividade menciona mapa de empatia de persona primária e secundária; portanto, a equipe poderia ter esclarecido melhor por que optou por trabalhar apenas com a persona principal.

**Recomendação:** inserir autoria, garantir que todas as imagens estejam versionadas no repositório e, se possível, criar uma segunda persona primária ou complementar a Dra. Helena com variações de perfil profissional, como neuropediatra em clínica pública versus neuropsicóloga em consultório privado.

## Cenário de análise/problema

O cenário de análise/problema é um dos pontos fortes do projeto. A narrativa tem título, atores e descreve uma situação problemática atual sem antecipar a solução VITA. A história evidencia carga cognitiva, pressão temporal, subjetividade, ansiedade familiar e dificuldade de observação de microexpressões. Isso está correto: cenário de problema deve narrar a situação indesejada no mundo atual, e não vender a solução.

As questões de refinamento cobrem os elementos esperados: ambiente/contexto, atores, objetivos, planejamento, ações, eventos e avaliação. O refinamento posterior também utiliza colchetes para indicar os trechos adicionados, como solicitado. Essa marcação facilita visualizar como as perguntas melhoraram a narrativa original.

Do ponto de vista conceitual, o cenário mostra boa compreensão de que uma interface surge para mediar uma atividade humana situada. A equipe não parte de “criar uma tela”, mas de um problema vivido por uma profissional em um ambiente com ruído, pressão, incerteza e consequências sociais.

**Recomendação:** manter esse padrão de escrita nas demais entregas. O mesmo nível de detalhamento contextual deveria alimentar com mais rigor os modelos formais, especialmente MoLIC e análise de tarefas.

## Análise de tarefas: HTA, GOMS e CTT

A equipe entregou dois conjuntos de HTA, GOMS e CTT, correspondendo aos dois integrantes identificados. Isso atende ao requisito quantitativo mínimo. As funcionalidades escolhidas são relevantes: submissão de imagem, inspeção de mapa de calor, leitura de relatório, feedback humano, análise de contribuição regional e exportação de relatório.

O HTA apresenta decomposição hierárquica e diagramas em árvore, o que é adequado. Porém, falta a tabela auxiliar exigida nas regras. A atividade zero deveria explicitar input, feedback e plano. As demais linhas não deveriam repetir input e feedback, mas deveriam trazer recomendações e problemas em pelo menos algumas atividades. Sem essa tabela, o HTA fica muito próximo de uma simples lista de passos e perde parte do seu valor analítico para identificar problemas de execução e requisitos de interface.

O GOMS está parcialmente adequado. Há objetivos, métodos, regras de seleção e operadores. O ponto frágil é que a regra de seleção aparece mesmo quando existe apenas um método. Em GOMS, a seleção é mais significativa quando há alternativas de método e uma condição que define qual usar. A equipe poderia enriquecer o modelo com alternativas, por exemplo: validar visualmente pelo heatmap, validar pelo relatório textual ou validar pelo gráfico regional, cada um com regras de seleção diferentes.

O CTT é o ponto mais frágil dentro da análise de tarefas. A equipe apresenta apenas relações sequenciais (`>>`). Como a regra de correção pede avaliar concorrência entre atividades, os CTTs deveriam usar operadores de concorrência, independência, escolha ou sincronização quando apropriado. Por exemplo, ao analisar o resultado, o usuário pode alternar entre heatmap, gráfico regional e relatório; isso poderia ser modelado com relações não puramente lineares. O CTT entregue se aproxima de um fluxo de passos, não de uma modelagem rica de tarefas concorrentes.

**Recomendação:** refazer os HTAs com tabela auxiliar completa e revisar os CTTs para incluir operadores temporais adequados. A equipe deve diferenciar claramente: HTA decompõe objetivos; GOMS modela metas, métodos, operadores e regras; CTT modela relações temporais entre tarefas do usuário, do sistema, interativas e abstratas.

## Prototipação

A prototipação foi bem executada e bem documentada. A equipe identificou tarefas importantes, construiu um fluxo de interação, apresentou telas numeradas em baixa fidelidade textual e depois anexou telas finais implementadas. O fluxo Upload → Análise XAI → Relatórios → Feedback é claro e coerente com a jornada proposta.

O teste com colega foi documentado com tarefa, perfil do testador, críticas, severidade e recomendações. Esse é um ponto bastante positivo, pois mostra que a prototipação foi usada para aprender com a interação, não apenas para desenhar telas. As críticas levantadas são pertinentes: falta de clareza do gráfico de contribuição regional, ambiguidade nos níveis de explicação, baixa saliência de campos obrigatórios, dúvida sobre feedback opcional e navegação sequencial pouco explícita.

As telas finais estão presentes e mostram um sistema com boa qualidade visual: stepper superior, área de upload, predição, confiança, mapa de calor, gráfico regional, relatório e feedback. Isso atende ao requisito de protótipo final mesmo sem link Figma.

O principal ponto de atenção é o alinhamento entre protótipo, modelos formais e avaliação. Algumas telas mostram etapas como “Qualidade da Imagem”, mas essa etapa não aparece com a mesma força no MoLIC e nos modelos conceituais. Esse desalinhamento não invalida a entrega, mas indica que o projeto evoluiu visualmente sem atualizar todos os artefatos conceituais.

**Recomendação:** atualizar os modelos formais a partir do protótipo final. Em IHC, telas, tarefas, signos e fluxos conversacionais precisam evoluir juntos.

## Coleta de dados

A coleta de dados está bem estruturada. A equipe responde “que dados coletar” e “de quem coletar”, contemplando dados do usuário, relação com tecnologia, conhecimento de domínio, tarefas, motivações e valores. Também identifica corretamente profissionais de saúde como público de coleta.

A seção ética é adequada e importante para o domínio do projeto. O sistema lida com imagens faciais de crianças e inferências clínicas, o que envolve dados sensíveis, consentimento, confidencialidade, risco de viés e risco de uso indevido. A equipe acerta ao tratar o VITA como apoio à decisão, não como substituto do diagnóstico profissional.

As três técnicas escolhidas são adequadas: entrevista semiestruturada, questionário e investigação contextual. Todas possuem objetivo, forma de aplicação e instrumento. Isso atende bem ao enunciado.

O que poderia melhorar é a materialização dos instrumentos. O roteiro de entrevista tem poucas perguntas, o questionário traz exemplos, e a investigação contextual aparece como checklist. Para uma entrega excelente, seria esperado um instrumento mais pronto para aplicação: questionário completo, roteiro com abertura/fechamento, critérios de recrutamento, termo de consentimento e protocolo de registro.

**Recomendação:** transformar os instrumentos em anexos aplicáveis, com perguntas completas, escala de resposta, instruções ao aplicador e campos de registro.

## Ciclo de vida de engenharia de usabilidade

A equipe apresenta bem as características da plataforma. A descrição do software, hardware, capacidades e restrições é coerente com a proposta técnica do VITA. A relação entre GPU, backend, qualidade da imagem, conexão de internet e interpretabilidade por XAI mostra boa consciência das restrições reais de uso.

A tabela de princípios gerais também está satisfatória ao incluir contexto, LGPD, acessibilidade, ISO 9241 e diretrizes éticas. A contextualização clínica é boa e reforça que o sistema precisa considerar privacidade, segurança, acessibilidade e responsabilidade profissional.

A principal falha está nas metas quantitativas de usabilidade. As regras indicam que não se deve usar apenas eficácia, eficiência e satisfação. O esperado era trabalhar com cinco elementos clássicos, como facilidade de aprendizado, facilidade de recordação, eficiência, segurança no uso e satisfação. A equipe usa eficácia, eficiência, satisfação/confiança e facilidade de aprendizado, mas omite claramente facilidade de recordação e segurança no uso. Além disso, “eficácia” aparece misturada com acurácia clínica e predição do modelo, o que pode deslocar o foco da avaliação de usabilidade para desempenho algorítmico.

Em IHC, uma meta quantitativa de usabilidade deve ser mensurável na interação. Por exemplo: “90% dos usuários conseguem fazer upload sem ajuda em até 30 segundos”, “80% localizam o relatório na primeira tentativa”, “nenhum usuário envia feedback sem selecionar confirmação/correção”. A acurácia do modelo pode ser requisito técnico, mas não substitui métrica de usabilidade.

**Recomendação:** refazer a tabela de metas quantitativas com cinco fatores e métricas observáveis. Incluir explicitamente segurança no uso, pois o próprio projeto identificou risco de feedback incorreto, autodiagnóstico e uso por leigos.

## Modelo conceitual: cenários de interação, DCC, objetivos e signos

O cenário de interação está bem conectado ao cenário de problema. A equipe marca em negrito as intervenções do sistema e mostra como o VITA altera a atividade do profissional: upload, predição, heatmap, relatório e feedback. Essa transição problema → interação é adequada.

O Design Centrado na Comunicação também está bom. A tabela mostra tópicos, subtópicos, falas do usuário e falas do sistema/preposto. A equipe compreendeu a lógica comunicacional: o sistema não é apenas uma ferramenta, mas um interlocutor projetado que pede, mostra, explica e confirma informações.

O mapa de objetivos em Mermaid é coerente e alinha objetivos de alto nível a subobjetivos: reduzir subjetividade, diminuir carga cognitiva, auditar decisão computacional e acompanhar evolução. O ponto faltante é que a regra solicitava mapas individuais e um diagrama de consolidação. O projeto apresenta apenas um mapa consolidado.

O esquema conceitual de signos está em formato consolidado, o que é positivo. A tabela reúne signo, origem/observação, tipo, restrição, valor default, prevenção e recuperação. Porém, a cobertura de signos é pequena para a riqueza do sistema. Há signos para nome do paciente, arquivos, data e feedback, mas faltam signos centrais como score, confiança, mapa de calor, contribuição regional, relatório explicativo, status de processamento, qualidade da imagem e alertas de erro.

**Recomendação:** ampliar o esquema de signos para cobrir os elementos efetivamente presentes nas telas. Em especial, modelar signos de entrada, saída, estado e recuperação de erro.

## MoLIC

A entrega de MoLIC é a principal falha conceitual do projeto. O arquivo apresenta dois fluxogramas Mermaid com estados, ações do usuário e ações do sistema. Embora esses fluxos ajudem a entender a navegação, eles não constituem um diagrama MoLIC completo.

MoLIC exige uma representação da interação como conversa. As cenas devem conter os signos manipulados ou comunicados; as transições devem representar falas de usuário ou do preposto; e os mecanismos de breakdown/recuperação precisam estar modelados com a notação apropriada. Também era obrigatório haver processamento interno representado pela caixa preta preenchida. Esse símbolo não aparece.

Os fluxos de cancelamento ou recuperação também não estão representados como fluxos tracejados adequados. A equipe usa nós chamados “Breakdown”, mas eles funcionam como caixas genéricas de erro, não como a estrutura esperada da MoLIC. Além disso, as cenas “Aguardando solicitação”, “Processando dados” e “Exibindo resultado” não mostram entradas e saídas/signos de forma sistemática.

O problema não é a ausência de raciocínio. A equipe entende o fluxo do sistema. O problema é que o artefato entregue não respeita a linguagem formal pedida. Em uma disciplina de IHC, isso é relevante porque a notação existe justamente para modelar a conversa usuário-sistema antes da implementação.

**Recomendação:** refazer o MoLIC usando cenas com signos explícitos, falas de transição, rupturas comunicativas, recuperação/cancelamento e caixa preta de processamento. O cenário de upload, validação de qualidade, processamento XAI, exibição de resultado e feedback é um ótimo candidato para uma modelagem MoLIC correta.

## Protótipo final / Figma

A ausência de link Figma não deve ser penalizada, pois as regras permitem aceitar telas finais do sistema em alta fidelidade. O repositório possui telas implementadas que demonstram a interface final, incluindo upload, análise, relatório e feedback.

Visualmente, as telas indicam uma boa preocupação com hierarquia de informação. O sistema diferencia predição, confiança, mapa de calor, gráfico e relatório. A interface também reforça a ideia de apoio diagnóstico, o que é adequado eticamente.

O ponto a melhorar é a correspondência com o MoLIC. Como o MoLIC está fraco, não é possível afirmar que as telas finais derivam corretamente da modelagem conversacional. As telas estão boas, mas o vínculo formal entre modelo e protótipo precisa ser reconstruído.

**Recomendação:** após refazer o MoLIC, criar uma tabela de rastreabilidade: cena MoLIC → tela/protótipo → signos na interface → tarefa apoiada.

## Planejamento da avaliação pelo DECIDE

O planejamento com DECIDE está bem contextualizado. A equipe determina objetivos, explora perguntas, escolhe métodos, identifica questões práticas, trata ética e propõe formas de avaliar, interpretar e apresentar dados. O domínio clínico aparece de forma coerente em todas as etapas.

O ponto positivo mais importante é que a equipe não planeja avaliar apenas “se a tela é bonita”. Ela propõe avaliar upload, compreensão de mapas de calor, relatório em linguagem natural, confiança e feedback loop. Isso está alinhado à proposta de Preece, Rogers e Sharp, em que a avaliação deve responder perguntas relevantes sobre o uso real do sistema.

A lista de instrumentos está presente: TCLE, questionários, tabela de observação e formulário de avaliação heurística. Porém, parte do material está em formato HTML e poderia estar mais organizado como Markdown. Além disso, os instrumentos são descritos conceitualmente, mas nem todos estão prontos para aplicação. Por exemplo, o TCLE não está completo como documento; o questionário aparece mais como orientação do que como formulário final.

**Recomendação:** padronizar em Markdown e anexar instrumentos finais: TCLE completo, questionário pré/pós, tabela de observação e formulário de heurística com campos preenchíveis.

## Inspeção heurística

A inspeção heurística é insuficiente diante do que foi solicitado. A equipe apresenta apenas uma violação: envio de feedback em branco no módulo de feedback. A violação é relevante e bem justificada, especialmente pelo risco de comprometer o feedback loop e o aprendizado ativo. A severidade também foi classificada.

Entretanto, a atividade exigia uma avaliação de IHC por inspeção heurística cobrindo todas as telas do projeto, com uma solução completa por pessoa da equipe. Considerando que há duas pessoas e quatro telas principais, uma única violação não demonstra uma inspeção sistemática. A própria prototipação já identificou problemas que poderiam ter sido convertidos em violações heurísticas, como:

- gráfico de contribuição regional sem explicação clara;
- níveis “Básica/Detalhada/Técnica” ambíguos;
- campo obrigatório pouco visível;
- fluxo sequencial não evidente;
- feedback opcional com baixa saliência.

Esses problemas poderiam ser classificados em heurísticas como visibilidade do status, reconhecimento em vez de lembrança, prevenção de erros, consistência e padrões, e compatibilidade com o mundo real.

Também há problema com os prints. A tabela usa um placeholder/link de edição da própria Wiki, não um print real da interface. A seção de boas práticas lista dez exemplos, mas também não apresenta telas ilustrando cada heurística atendida. Pelas regras, era importante validar visualmente as violações ou os bons usos de heurística.

A equipe deve tomar cuidado para não transformar avaliação heurística em avaliação de segurança da informação apenas. Segurança é muito relevante no VITA, mas a inspeção heurística deve primeiro localizar problemas de interação na interface e classificá-los segundo as heurísticas de Nielsen.

**Recomendação:** refazer a inspeção com pelo menos uma tabela por avaliador ou uma matriz consolidada indicando avaliador, tela, print, heurística, problema, severidade e recomendação. Usar as quatro telas principais e registrar somente violações na parte avaliativa principal.

## Avaliação de usabilidade por observação do usuário

A avaliação por observação é uma das melhores partes do projeto. A equipe avaliou três usuários reais ou representativos do domínio, número superior ao mínimo esperado para uma equipe de dois integrantes. Foram definidos fluxograma, procedimento, tarefas, formulário de perfil, TCLE, tabela de métricas, resultados por usuário, links de evidências, respostas pós-teste e conclusão.

As tarefas são coerentes com o sistema: upload, inspeção de score/mapa, análise de gráfico regional, leitura do relatório e uso do feedback loop. A tabela de resultados registra grau de sucesso, erros, tipos de erros, tempo e satisfação, exatamente os tipos de dados esperados em um teste de usabilidade por observação.

A conclusão é boa porque não se limita a dizer que “os usuários gostaram”. Ela identifica problemas reais: superficialidade de fotos estáticas, risco de uso indevido, necessidade de validação de imagem, controle de acesso e evolução para análise multimodal. Esse é um uso maduro da observação, pois transforma evidência empírica em requisito de redesign.

Há, contudo, problemas de forma. O arquivo parece conter conteúdo duplicado: depois da conclusão, o documento reinicia uma segunda versão da avaliação. Além disso, na segunda ocorrência, os links de vídeo aparecem parcialmente vazios ou sem URL. Esse tipo de duplicidade prejudica a clareza da entrega e pode confundir a correção.

Também é importante observar que uma das participantes é psicopedagoga. Ela é uma stakeholder relevante, mas a equipe deve justificar melhor se ela representa o usuário primário ou um usuário secundário, porque o sistema foi inicialmente direcionado a psicólogos, psiquiatras e neuropediatras.

**Recomendação:** limpar duplicidades, manter apenas a versão mais completa, validar os links de evidência e explicitar a relação de cada participante com o público-alvo primário ou secundário.

## Problemas transversais de organização e versionamento

Alguns problemas aparecem em várias partes do projeto:

- há imagens referenciadas por caminhos relativos que não foram encontradas, como `imagens/empatia.png` e `imagens/ciclo_de_vida.png`;
- algumas URLs de imagens com parênteses no nome podem quebrar no Markdown se não forem corretamente codificadas;
- parte das evidências está em links externos, o que torna a correção dependente de permissões e disponibilidade fora do repositório;
- há desalinhamento entre artefatos: protótipo final tem elementos que não aparecem em MoLIC, CTT ou signos conceituais.

**Recomendação:** seguir a organização dos projetos-modelo: manter documentos em Markdown, imagens versionadas em diretórios próprios, links relativos funcionando e rastreabilidade entre problema, tarefas, signos, MoLIC, protótipo e avaliação.

## Correções prioritárias

A prioridade máxima é refazer o MoLIC e a inspeção heurística. Esses dois itens estão conceitualmente abaixo do restante do projeto e impactam fortemente a avaliação global.

A segunda prioridade é revisar a análise de tarefas, principalmente HTA e CTT. Os HTAs precisam de tabela auxiliar completa; os CTTs precisam representar concorrência e relações temporais próprias da notação.

A terceira prioridade é corrigir as metas quantitativas de usabilidade no ciclo de vida, separando métricas de interação de métricas de desempenho do modelo de IA.

A quarta prioridade é incorporar prints e análises visuais na análise de concorrência, em vez de depender de link externo.

A quinta prioridade é limpar problemas de organização: links quebrados, imagens ausentes, duplicidade de conteúdo e arquivos em HTML.

## Parecer final

O projeto demonstra boa maturidade de domínio, boa articulação entre problema real e proposta de interface, e excelente potencial como projeto de IHC aplicado a um contexto crítico. A equipe soube construir uma narrativa consistente: problema clínico, persona, cenário, jornada, protótipo, teste e observação empírica.

Entretanto, a entrega não está plenamente completa porque alguns artefatos formais foram tratados como fluxos descritivos, não como modelos de IHC. Isso é mais evidente em MoLIC, CTT e inspeção heurística. A equipe domina a ideia do sistema, mas precisa maior rigor metodológico na representação das técnicas.

Em termos pedagógicos, o VITA é um bom projeto, com partes muito fortes, mas com pendências relevantes em técnicas centrais. Com a correção do MoLIC, ampliação da inspeção heurística e revisão da análise de tarefas, o trabalho poderia atingir um nível significativamente mais alto de completude.


## Referências conceituais usadas como base de correção

- BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. *Interação Humano-Computador*. Rio de Janeiro: Elsevier, 2010.
- PREECE, Jennifer; ROGERS, Yvonne; SHARP, Helen. *Interaction Design: Beyond Human-Computer Interaction*. Wiley.
- NIELSEN, Jakob. *Usability Engineering*. Morgan Kaufmann, 1993.
- NIELSEN, Jakob; MOLICH, Rolf. Heuristic evaluation of user interfaces.
- CARROLL, John M. *Making Use: Scenario-Based Design of Human-Computer Interactions*. MIT Press.
- CARD, Stuart; MORAN, Thomas; NEWELL, Allen. *The Psychology of Human-Computer Interaction*. Lawrence Erlbaum.
- ISO 9241-11 e ISO 9241-210, como referências para usabilidade e design centrado no ser humano.
