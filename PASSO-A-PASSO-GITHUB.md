# Passo a Passo GitHub

## Objetivo

Criar um repositorio publico apenas para download oficial e releases, sem expor o codigo-fonte de trabalho.

## Nome recomendado

`aztex-overforge-download`

## Descricao curta

`Download oficial do AzteX Overforge, com releases publicas, hashes e instrucoes de uso.`

## Como criar

1. entre em `github.com`
2. faca login
3. clique em `New repository`
4. nomeie como `aztex-overforge-download`
5. marque como `Public`
6. nao precisa adicionar `README` se voce for subir os arquivos desta pasta
7. clique em `Create repository`

## O que subir no repositorio

Suba apenas os arquivos desta pasta:

- `README.md`
- `.gitignore`
- `RELEASE-TEMPLATE.md`
- `PASSO-A-PASSO-GITHUB.md`

## O que nao subir

- o codigo do produto
- a pasta `vendor`
- a chave privada
- a pasta `state`
- bundles ou arquivos de clientes

## Como publicar a release

1. abra o repositorio no GitHub
2. clique em `Releases`
3. clique em `Draft a new release`
4. tag: `v2.9.0`
5. title: `AzteX Overforge v2.9.0`
6. copie o texto de `RELEASE-TEMPLATE.md`
7. anexe:
   - `AzteX-Overforge-v2.9.0.exe`
   - `AzteX-Overforge-v2.9.0.zip`
   - `SHA256SUMS.txt`
8. publique a release

## Link para divulgar

Depois de publicar, divulgue no Discord o link da release, nao o arquivo solto.
