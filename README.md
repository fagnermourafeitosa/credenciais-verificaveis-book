# Credenciais Verificáveis

**Identidade digital, provas de conhecimento zero e agentes de IA sob controle**


Como provar que você tem idade suficiente sem revelar sua data de nascimento? Como apresentar um documento digital cuja autenticidade possa ser verificada? E como permitir que um agente de IA aja em seu nome, com permissões limitadas e ações auditáveis?

Este repositório disponibiliza o livro **Credenciais Verificáveis**, uma jornada pelos fundamentos, protocolos e decisões de arquitetura que conectam identidade digital, privacidade e governança de agentes.

[![Downloads do PDF nas Releases](https://img.shields.io/github/downloads/fagnermourafeitosa/credenciais-verificaveis-book/credenciais_verificaveis_livro.pdf?label=Downloads%20do%20PDF&color=ac4728)](https://github.com/fagnermourafeitosa/credenciais-verificaveis-book/releases)

**[Ler o livro em PDF](./credenciais_verificaveis_livro.pdf)** · **[Baixar o PDF](https://github.com/fagnermourafeitosa/credenciais-verificaveis-book/releases/latest/download/credenciais_verificaveis_livro.pdf)**

[![Comprar o livro impresso na UICLAP](https://img.shields.io/badge/Comprar_o_livro_impresso-UICLAP-ac4728?style=for-the-badge)](https://loja.uiclap.com/titulo/ua214620/)

## Sobre o livro

A obra parte de um problema cotidiano: serviços digitais frequentemente coletam documentos inteiros quando precisam comprovar apenas uma informação. A partir desse cenário, apresenta mecanismos para verificar afirmações, reduzir a exposição de dados e controlar o que pessoas e agentes podem fazer em um sistema.

Um exemplo acompanha a leitura: Maria quer alugar um carro em Lisboa. A cada etapa, o cenário evolui da verificação de uma habilitação à comprovação de idade e à delegação da reserva a um agente de IA. Um segundo caso, de comprovação de renda, aprofunda a discussão sobre privacidade e provas de conhecimento zero.

O percurso é organizado em seis perguntas de confiança:

- **Integridade:** os dados foram alterados desde que foram assinados?
- **Autenticidade:** quem assinou os dados e quem os apresenta?
- **Autoridade:** o emissor tem legitimidade para fazer essa afirmação?
- **Privacidade:** é possível provar o necessário sem revelar o restante?
- **Autorização:** a operação é permitida para aquele sujeito, recurso e contexto?
- **Delegação e governança:** em nome de quem o agente age, com quais limites e sob qual supervisão?

## Para quem é

O livro se destina a **desenvolvedores, arquitetos de software e profissionais de segurança** que precisam entender, projetar ou avaliar sistemas de identidade digital.

A leitura pressupõe familiaridade com HTTP, JSON e login em aplicações web. Os fundamentos de criptografia são construídos ao longo dos capítulos. Os exemplos em Python e linha de comando ilustram estruturas e fluxos, enquanto mensagens em JSON e JWT aproximam a discussão dos protocolos utilizados na prática.

## Conteúdo

São **13 capítulos em cinco partes**, acompanhados de um glossário e de um mapa de especificações e organizações.

| Parte | Capítulos | Temas centrais |
| --- | --- | --- |
| I · Identidade, criptografia e confiança | 1 a 3 | Identidade digital, OAuth e OpenID Connect, hashes, assinaturas digitais, certificados e cadeias de confiança. |
| II · Credenciais verificáveis e carteiras digitais | 4 a 6 | Emissores, titulares e verificadores; formatos de credenciais; emissão, armazenamento e apresentação por carteiras digitais. |
| III · Provar sem revelar | 7 a 9 | Divulgação seletiva, provas de conhecimento zero e comprovação de atributos com menor exposição de dados. |
| IV · Autorização e agentes | 10 a 12 | Políticas de acesso, delegação, limites de atuação, aprovação humana, revogação e auditoria de agentes. |
| V · Juntando as peças | 13 | Integração dos mecanismos em uma jornada completa, estado dos padrões e desafios em aberto. |

Entre as tecnologias e especificações discutidas estão **W3C Verifiable Credentials, DIDs, SD-JWT, mdoc, OpenID4VCI, OpenID4VP, DCQL, OpenID Federation, AuthZEN, OAuth Token Exchange e Shared Signals**.

> O estado de referência dos padrões descritos é **outubro de 2026**. O livro distingue padrões publicados, implementações experimentais e propostas em discussão. A composição dos mecanismos em uma jornada não implica a existência de um fluxo padronizado de ponta a ponta.

## Como citar

Referência bibliográfica sugerida:

> FEITOSA, Fagner Moura. **Credenciais verificáveis: identidade digital, provas de conhecimento zero e agentes de IA sob controle**. Edição de leitura. out. 2026. Disponível em: https://github.com/fagnermourafeitosa/credenciais-verificaveis-book.

### BibTeX

```bibtex
@book{feitosa2026credenciais,
  author   = {Feitosa, Fagner Moura},
  title    = {Credenciais Verificáveis: Identidade digital, provas de conhecimento zero e agentes de IA sob controle},
  year     = {2026},
  month    = oct,
  edition  = {Edição de leitura},
  language = {Portuguese},
  url      = {https://github.com/fagnermourafeitosa/credenciais-verificaveis-book}
}
```

## Correções e sugestões

Encontrou uma imprecisão, um erro de digitação ou um trecho que merece mais clareza? [Abra uma issue](https://github.com/fagnermourafeitosa/credenciais-verificaveis-book/issues), indicando o capítulo, a seção ou a página e descrevendo a correção sugerida. Para observações sobre especificações, inclua a referência e a versão consultada.

## Autor e direitos

**[Fagner Moura Feitosa](https://github.com/fagnermourafeitosa)**

© 2026 Fagner Moura Feitosa. **Todos os direitos reservados**, conforme indicado no livro. A disponibilização do PDF neste repositório não concede, por si só, licença para reprodução, adaptação ou redistribuição da obra.
