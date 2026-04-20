# My Project

> Este repositório foi criado usando o [Foral Template](https://github.com/foral-project/template).

## Setup

1. Edite `catalog-info.yaml` com os dados do seu projeto:
   - `metadata.name` → nome do projeto (RFC 1123: lowercase, hyphens)
   - `metadata.description` → descrição
   - `spec.owner` → owner (RFC 1123)
   - `spec.lifecycle` → `experimental`, `production`, ou `deprecated`

2. O CI já está configurado em `.github/workflows/foral.yml`:
   - ✅ Validação de schema (JSON Schema Draft 2020-12)
   - ✅ Validação de naming (RFC 1123)
   - ✅ Validação de commits (Conventional Commits 1.0.0)

3. (Opcional) Instale o CLI para validação local:

```bash
curl -sfL https://foral-project.github.io/protocol/install.sh | sh
foral validate
foral status
```

## Validação local

```bash
foral validate   # valida catalog-info.yaml
foral status     # dashboard de compliance
```

## Referências

- [Foral Protocol](https://github.com/foral-project/protocol/blob/main/PROTOCOL.md)
- [Guia de Adoção](https://github.com/foral-project/governance/blob/main/ADOPTING.md)
- [CLI](https://github.com/foral-project/cli)

## Licença

Apache-2.0
