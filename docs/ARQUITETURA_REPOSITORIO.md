# Arquitetura do repositorio — Folclore Vivo MILK

Este documento descreve a organizacao funcional do repositorio **Folclore Vivo — Metodologia de Pesquisa MILK**.

---

## Objetivo

Garantir que a pesquisa do Folclore Vivo possa crescer por regioes, figuras, fontes, variantes e leituras interpretativas sem perder rastreabilidade, autoria, consistencia metodologica ou possibilidade de verificacao.

---

## Estrutura funcional

### 1. Raiz

A raiz contem os documentos de leitura obrigatoria:

- `README.md` — apresentacao publica e mapa geral;
- `LICENSE.md` — licenca do repositorio;
- `NOTICE.md` — aviso de autoria e limites de uso;
- `GOVERNANCE.md` — regras de governanca documental;
- `CONTRIBUTING.md` — regras para contribuicoes;
- `investigadores.md` — nota institucional dos investigadores.

### 2. Metodologia

A pasta `metodologia/` contem o metodo replicavel:

- guia geral;
- criterios de selecao;
- estrutura padrao de entrada.

Nenhuma regiao deve criar estrutura propria incompatível com estes ficheiros sem decisao explicita.

### 3. Regioes

A pasta `regioes/` organiza a expansao territorial:

- Norte;
- Centro;
- Lisboa e Vale do Tejo;
- Alentejo;
- Algarve;
- Acores;
- Madeira.

Cada regiao deve ter `README.md`, pasta de figuras e ficheiro de fontes regionais quando houver material suficiente.

### 4. Recursos

A pasta `recursos/` contem elementos transversais:

- bibliografia geral;
- arquivo de fontes;
- glossario.

### 5. Dados

A pasta `dados/` contem catalogos estruturados para leitura rapida, auditoria e futura interoperabilidade.

---

## Regra de crescimento

Novas entradas devem seguir esta ordem:

1. registo no catalogo;
2. criacao da entrada regional;
3. indicacao de fontes;
4. marcacao de estado;
5. revisao;
6. publicacao controlada.

---

## Compatibilidade futura

A estrutura foi preparada para dialogar futuramente com:

- Atlas Vivo MILK;
- bases bibliograficas;
- inventarios patrimoniais;
- mapas territoriais;
- fichas curatoriais;
- publicacoes e dispositivos culturais.

---

*Associacao MILK — Movimento de Intervencoes e Linguagens Kulturais e Arte*
