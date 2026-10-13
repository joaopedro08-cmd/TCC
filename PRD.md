# PRD - Aplicativo Interativo de Situações Emergenciais

**Status:** rascunho para o Pré-TCC  
**Plataforma inicial:** aplicação web para computador  
**Público inicial:** pessoas a partir de 10 anos  
**Modelo:** gratuito e sem anúncios

## 1. Visão do produto

Criar uma aplicação web educativa que torne o aprendizado de primeiros socorros mais acessível e envolvente. O produto deve ajudar pessoas interessadas no tema a adquirir conhecimento, sentir mais confiança e aprender como agir em diferentes situações, usando quizzes, missões e conquistas.

O projeto começa como um protótipo web para o Pré-TCC. A intenção futura é ampliar o acesso para celulares Android e iOS. O produto será educativo; não será uma ferramenta de orientação em tempo real durante emergências.

## 2. Problema e oportunidade

Pessoas interessadas em aprender primeiros socorros podem ter dificuldade de acesso a conteúdos educativos ou considerar os formatos disponíveis entediantes, o que pode desestimular a continuidade do aprendizado. Uma experiência interativa, organizada em etapas e com retorno sobre o desempenho pode tornar o estudo mais atraente.

A gamificação deve apoiar o aprendizado, não ser tratada como evidência de competência prática. Uma meta-análise de 2026 sobre jogos sérios para treinamento de RCP não encontrou vantagem estatisticamente significativa sobre métodos tradicionais nos resultados avaliados e destacou limitações e heterogeneidade dos estudos. Portanto, o protótipo deve permitir avaliar conhecimento e frequência de uso, sem afirmar que quizzes certificam habilidade prática.

## 3. Público-alvo

- Pessoas com mais de 10 anos que tenham interesse em aprender primeiros socorros.
- Aprendizagem inicialmente individual.
- Uso em cursos de primeiros socorros é uma possibilidade futura, ainda não definida.
- O conteúdo será igual para todas as idades. A adequação da linguagem e dos exemplos para pessoas a partir de 10 anos precisa ser avaliada durante o projeto.

## 4. Objetivos

1. Facilitar o acesso ao aprendizado de primeiros socorros.
2. Reduzir a insegurança e aumentar o conhecimento dos usuários.
3. Ensinar conceitos e condutas por meio de quizzes e situações interativas.
4. Incentivar a continuidade dos estudos com progressão, missões, conquistas e revisões.
5. Avaliar o sucesso principalmente pela frequência de uso e pelo conhecimento aprendido.

## 5. Princípios e limites

- O aplicativo é educativo e requer conexão com a internet.
- Não oferece triagem, diagnóstico, atendimento remoto nem instruções operacionais para uma emergência em andamento.
- Não substitui treinamento presencial, profissionais de emergência ou atendimento médico.
- O conteúdo de primeiros socorros deverá ser fundamentado em fontes confiáveis, ter responsáveis pela revisão e apresentar data de atualização.
- Nenhum tema será excluído do produto final; os temas serão apresentados gradualmente conforme o avanço do usuário.
- O lançamento começa com foco no Brasil. Uma expansão internacional poderá exigir localização de idioma, serviços de emergência e recomendações aplicáveis a cada país.
- O aplicativo será gratuito e não exibirá anúncios.

## 6. Escopo do protótipo

### Incluído

- Aplicação web, com experiência inicial voltada a computadores e acesso pela internet.
- Percurso de aprendizagem dividido em etapas, com progressão gradual e temas bloqueados até o avanço apropriado.
- Quizzes como atividade central de aprendizagem.
- Missões associadas à realização de quizzes.
- Pontuação, níveis, conquistas, sequência de estudos, missões periódicas, avatar e ranking como elementos previstos para a experiência gamificada.
- Revisão de conteúdo ao longo do tempo. A seleção de questões para revisão deve considerar respostas incorretas e conteúdos já estudados.
- Acompanhamento de progresso e resultados individuais.
- Interface e conteúdo em português do Brasil para a primeira versão.

### Fora do escopo inicial

- Aplicativos nativos para Android e iOS; são uma possibilidade futura.
- Funcionamento sem internet.
- Instruções em tempo real para emergências, acionamento de socorro ou localização de serviços.
- Avaliação de habilidades físicas, uso de manequins ou certificação de primeiros socorros.
- Uso em cursos ou gestão de turmas, até que essa possibilidade seja definida.
- Conteúdo localizado para outros países na primeira versão.

## 7. Requisitos funcionais

**RF-01 - Acesso ao conteúdo:** o usuário deve conseguir acessar os módulos de aprendizagem pela aplicação web.

**RF-02 - Progressão:** o sistema deve organizar os temas em uma progressão e liberar etapas gradualmente, em vez de apresentar todo o catálogo de uma vez.

**RF-03 - Quizzes:** o usuário deve conseguir responder quizzes relacionados ao conteúdo estudado e receber retorno sobre seu desempenho. Formatos de questão e regras de aprovação ainda serão definidos.

**RF-04 - Missões:** o sistema deve associar missões à realização de atividades e quizzes.

**RF-05 - Gamificação:** o sistema deve prever pontos, níveis, conquistas, sequência de estudos, missões periódicas, avatar e ranking. Regras, visibilidade e interação social ainda serão definidas.

**RF-06 - Revisão:** o sistema deve oferecer oportunidades de revisão do conteúdo ao longo do tempo, incluindo material relacionado a respostas incorretas.

**RF-07 - Progresso:** o usuário deve conseguir acompanhar sua evolução, os conteúdos concluídos e suas conquistas. Persistência local, sincronização e necessidade de conta estão pendentes de definição.

**RF-08 - Gratuidade:** a experiência não deve cobrar do usuário nem apresentar anúncios.

## 8. Requisitos não funcionais

- A aplicação deve funcionar em navegadores web com conexão à internet.
- A interface deve ser clara e compreensível para pessoas a partir de 10 anos.
- O conteúdo deve ser revisável e permitir registrar fonte, responsável e data de atualização.
- A coleta de dados deve ser minimizada; dados de perfil, ranking, analytics e requisitos de privacidade para menores ainda precisam ser definidos.
- A futura expansão para dispositivos móveis não deve exigir que o protótipo seja tratado como aplicativo nativo.

## 9. Métricas de sucesso

As duas métricas principais, definidas pelo projeto, são:

- **Frequência de uso:** deverá ser operacionalizada, por exemplo, como sessões por usuário em um período ou retorno ao aplicativo.
- **Conhecimento aprendido:** deverá ser avaliado com uma medida antes e depois de um conjunto de atividades ou módulos.

Metas numéricas, período de medição, instrumento de avaliação e forma de coleta serão definidos antes da avaliação do protótipo. A frequência de uso, isoladamente, não deve ser interpretada como aprendizagem.

## 10. Conteúdo e segurança

Ainda não foram definidos especialistas, fontes de conteúdo ou processo de revisão. Isso é uma pendência importante: conteúdo clínico não deve ser publicado como orientação validada sem revisão apropriada. Para o protótipo, usar conteúdo demonstrativo revisado ou deixar explícito que se trata de conteúdo ilustrativo, sem apresentar condutas não verificadas.

Referências iniciais para pesquisa e desenho do conteúdo:

- [IFRC - International First Aid, Resuscitation and Education Guidelines 2025](https://www.ifrc.org/document/ifrc-international-first-aid-resuscitation-and-education-guidelines-2025)
- [European Resuscitation Council - Guidelines 2025](https://www.erc.edu/science-research/guidelines/guidelines-2025/guidelines-2025-english/)
- [Ministério da Saúde - Serviço de Atendimento Móvel de Urgência (SAMU 192)](https://www.gov.br/saude/pt-br/composicao/saes/samu-192)
- [Chen et al. - Using serious games for cardiopulmonary resuscitation training: a meta-analysis and systematic review (2026)](https://doi.org/10.3389/fpubh.2026.1726862)
- [American Red Cross - First Aid app, referência de produto](https://play.google.com/store/apps/details?id=com.cube.arc.fa)

## 11. Decisões pendentes

1. Definir quais módulos e quizzes estarão disponíveis no protótipo e a ordem de progressão.
2. Definir fontes, revisão por especialista, atribuição de responsabilidade e atualização do conteúdo.
3. Definir formatos de questão, feedback, pontuação e critérios de conclusão.
4. Definir como funcionam missões, sequência diária, conquistas, avatar e ranking, incluindo se ranking será individual, entre amigos ou público.
5. Definir se haverá conta de usuário e como progresso será persistido e sincronizado.
6. Definir como apresentar conteúdo e exemplos adequados ao público a partir de 10 anos, mantendo a decisão de não separar o conteúdo por idade.
7. Definir privacidade, consentimento e proteção de dados para usuários menores de idade.
8. Definir instrumento, metas e período de avaliação de frequência de uso e conhecimento aprendido.
9. Definir até que ponto o protótipo será adaptado a telas de celular.

## 12. Premissas

- O protótipo representa a proposta e permite avaliar sua experiência; não equivale a um produto clínico validado ou a um curso certificador.
- O catálogo completo é uma visão de produto final; a progressão deve evitar mostrar todos os temas como disponíveis desde o início.
- A aplicação web exigirá internet para acesso. Uma futura estratégia de sincronização não implica suporte offline.
