# Credenciais Verificáveis

**Identidade digital, provas de conhecimento zero e agentes de IA sob controle**

Maria quer alugar um carro. A locadora precisa conferir a habilitação e a idade mínima. Mais adiante, ela passa a usar um sistema com agentes de IA para pesquisar ofertas e cuidar da reserva. Como reconhecer um documento legítimo, expor menos dados e limitar o que o assistente pode fazer em seu nome?

**Credenciais Verificáveis**, de **Fagner Moura**, acompanha esse cenário desde as assinaturas digitais e as cadeias de confiança até as carteiras, os modelos de acesso e a delegação a agentes.

[![Downloads do PDF nas Releases](https://img.shields.io/github/downloads/fagnermourafeitosa/credenciais-verificaveis-book/credenciais_verificaveis_livro.pdf?label=Downloads%20do%20PDF&color=ac4728&displayAssetName=false)](https://github.com/fagnermourafeitosa/credenciais-verificaveis-book/releases)

**[Ler o livro em PDF](./credenciais_verificaveis_livro.pdf)** · **[Baixar o PDF](https://github.com/fagnermourafeitosa/credenciais-verificaveis-book/releases/latest/download/credenciais_verificaveis_livro.pdf)**

[![Comprar o livro impresso na UICLAP](https://img.shields.io/badge/Comprar_o_livro_impresso-UICLAP-ac4728?style=for-the-badge)](https://loja.uiclap.com/titulo/ua214620/)

## Sobre o livro

O ponto de partida é a diferença entre reconhecer uma conta e comprovar um atributo. O livro explica como conferir a origem de um documento, reconhecer a autoridade do emissor e vincular a credencial ao titular. Em seguida, acompanha a emissão por OpenID4VCI e a apresentação por OpenID4VP.

Na parte dedicada à privacidade, distingue divulgação seletiva de provas de conhecimento zero e examina o que cada abordagem permite ocultar. Um segundo exemplo, sobre comprovação de renda, mostra o problema de entregar o valor exato quando o serviço precisa saber apenas se ele alcança um limite.

Quando Maria delega essa tarefa, o foco passa às regras de acesso: quais ferramentas o sistema pode chamar, sob quais condições e quando precisa pedir o aceite da titular. OAuth, MCP e AuthZEN entram nesse contexto, junto aos meios de revogar o acesso e auditar as ações executadas.

Seis perguntas orientam a leitura:

- **Integridade:** os dados foram alterados desde que foram assinados?
- **Autenticidade:** quem assinou os dados e quem os apresenta?
- **Autoridade:** o emissor tem legitimidade para fazer essa afirmação?
- **Privacidade:** é possível provar o necessário sem revelar o restante?
- **Autorização:** quem pode executar a operação, sobre qual recurso e em que contexto?
- **Delegação e governança:** quem o agente representa, quais são seus limites e como supervisionar suas ações?

## Para quem é

O livro se destina a **desenvolvedores, arquitetos de software e profissionais de segurança** que precisam entender, projetar ou avaliar sistemas de identidade digital.

A leitura pressupõe familiaridade com HTTP, JSON e login em aplicações web. Os fundamentos de criptografia são construídos ao longo dos capítulos. Os exemplos em Python e linha de comando ilustram estruturas e fluxos, enquanto mensagens em JSON e JWT aproximam a discussão dos protocolos utilizados na prática.

## Conteúdo

São **13 capítulos em cinco partes**, um bônus sobre o experimento do autor com Longfellow, dois apêndices e as referências.

| Parte | Capítulos | Temas centrais |
| --- | --- | --- |
| I · Identidade, criptografia e confiança | 1 a 3 | OAuth e OpenID Connect, hashes, assinaturas digitais, certificados, DIDs e autoridade do emissor. |
| II · Credenciais verificáveis e carteiras digitais | 4 a 6 | W3C VC, SD-JWT VC e mdoc; vinculação ao titular; emissão e apresentação com OpenID4VCI e OpenID4VP. |
| III · Provar sem revelar | 7 a 9 | Divulgação seletiva, correlação, predicados, provas de conhecimento zero e Longfellow. |
| IV · Autorização e agentes | 10 a 12 | RBAC, ReBAC e ABAC; OpenFGA e CEL; OAuth Token Exchange, MCP e AuthZEN; controle por chamada, aprovação humana, revogação e auditoria. |
| V · A reserva de Maria | 13 | O cenário completo, a comparação com o uso corporativo de agentes, o estado dos padrões e as questões em aberto. |

A parte sobre agentes também examina ID-JAG, COAZ-MCP e Shared Signals, distinguindo as propostas em discussão dos mecanismos já publicados.

### Bônus: Predicados sobre SD-JWT VC: um experimento com Longfellow

O estudo apresenta um circuito desenvolvido pelo autor para demonstrar condições sobre atributos ocultos de uma SD-JWT VC, mantendo ECDSA P-256 e SHA-256. Explica as restrições sobre o JWT, a ligação entre circuitos e o reaproveitamento do estado de SHA-256, com trechos de código, testes e medições exploratórias. Também registra as limitações encontradas e o que ainda falta para integrar o experimento a uma carteira.

O material de consulta inclui:

- **Apêndice A: Glossário de termos e siglas**, com definições e remissões aos capítulos.
- **Apêndice B: Guia de especificações**, organizado por organismo e assunto.
- **Referências**, com links para os documentos e estudos citados.

O texto distingue padrões publicados, implementações experimentais e propostas em discussão. A reserva de Maria reúne essas peças em um exemplo; o fluxo completo ainda não constitui um padrão único.

## Como citar

Referência bibliográfica sugerida:

> MOURA, Fagner. **Credenciais verificáveis: identidade digital, provas de conhecimento zero e agentes de IA sob controle**. 2026. Disponível em: https://github.com/fagnermourafeitosa/credenciais-verificaveis-book.

### BibTeX

```bibtex
@book{moura2026credenciais,
  author   = {Moura, Fagner},
  title    = {Credenciais Verificáveis: Identidade digital, provas de conhecimento zero e agentes de IA sob controle},
  year     = {2026},
  month    = oct,
  language = {Portuguese},
  url      = {https://github.com/fagnermourafeitosa/credenciais-verificaveis-book}
}
```

## Correções e sugestões

Encontrou uma imprecisão, um erro de digitação ou um trecho que merece mais clareza? [Abra uma issue](https://github.com/fagnermourafeitosa/credenciais-verificaveis-book/issues), indicando o capítulo, a seção ou a página e descrevendo a correção sugerida. Para observações sobre especificações, inclua a referência e a versão consultada.

## Autor e direitos

**[Fagner Moura](https://github.com/fagnermourafeitosa)** é Research Engineer na área de identidade digital. Pesquisa segurança da informação, criptografia, identidade autossoberana (SSI) e blockchain, e costuma resolver seus problemas em Python ou Go.

Trabalha no mercado corporativo e de startups desde 1999, com uma trajetória que passa por engenharia de software, segurança de aplicações e inteligência artificial aplicada.

É graduado em Data Science, com extensão pela PUC-Rio e especialização pela Unicamp.

© 2026 Fagner Moura. **Todos os direitos reservados**, conforme indicado no livro. A disponibilização do PDF neste repositório não concede, por si só, licença para reprodução, adaptação ou redistribuição da obra.
