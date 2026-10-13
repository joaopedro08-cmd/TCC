# Instrucoes do projeto

## Referencias e escopo

- Use [PRD.md](PRD.md) como fonte dos requisitos e [PROJETO_TECNICO.md](PROJETO_TECNICO.md) como proposta de arquitetura e implementacao.
- Diferencie decisoes aprovadas de itens marcados como pendentes. Nao transforme recomendacoes futuras em requisitos sem atualizar os documentos.
- O objetivo atual e um prototipo web para o Pre-TCC. A implementacao existente e uma pagina estatica em [index.html](index.html), sem framework, build ou backend.
- Nao introduza dependencias, framework, autenticacao, API, banco de dados, analytics ou ranking real sem necessidade confirmada no PRD.

## Interface e acessibilidade

- Preserve o design aprovado: moderno, minimalista, colorido e acolhedor, com acentos coral, menta, amarelo e azul-claro, superficies leves e ilustracao cartunesca discreta.
- Evite contornos escuros grossos, sombras duras, excesso de paineis, paletas predominantemente roxas, gradientes decorativos e animacoes constantes.
- Mantenha a interface responsiva, em portugues do Brasil, com texto claro para o publico definido no PRD.
- Use HTML semantico, controles utilizaveis por teclado, foco visivel, feedback acessivel e suporte a `prefers-reduced-motion`. Nunca indique estados apenas por cor.

## Seguranca do conteudo e privacidade

- O produto e exclusivamente educativo; nao implemente triagem, diagnostico ou orientacao em tempo real para emergencias.
- Nao invente nem altere protocolos clinicos de primeiros socorros sem fontes confiaveis e revisao por pessoa qualificada. Conteudo demonstrativo nao validado deve permanecer identificado como tal.
- Nao afirme que quizzes, pontos ou conquistas certificam habilidade pratica ou substituem treinamento presencial.
- O publico inclui pessoas a partir de 10 anos. Nao adicione coleta de dados pessoais, dados de saude, localizacao, contas ou rastreamento sem requisitos aprovados e avaliacao de privacidade apropriada.

## Validacao

- A pagina e estatica e pode ser aberta diretamente no navegador; nao inicie servidor de desenvolvimento sem necessidade tecnica.
- Apos alterar HTML, CSS ou JavaScript, verifique os diagnosticos do arquivo. Para mudancas no JavaScript embutido, valide a sintaxe com Node.js e, quando disponivel, teste a interacao no navegador.
- Nao declare testes automatizados ou verificacao visual como concluidos se as ferramentas correspondentes nao estiverem disponiveis.
