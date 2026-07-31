# Pareceres · Validação de Documentos

Catálogo dos **35 pareceres** emitidos pelos validadores, com os critérios de cada
documento marcados como **reprovador** ("Deve conferir") ou **informativo**.

Página única, autocontida: sem CSS, fonte, script ou imagem externos — abre igual
em qualquer navegador e não depende de rede.

## Grupos

| grupo | pareceres |
|---|---|
| Documento único | 12 |
| Treinamentos NR | 7 |
| Cruzamento com a Folha | 2 |
| Fluxo consolidado | 5 |
| Documento do fornecedor | 9 |

## Publicar no GitHub Pages

1. Crie o repositório no GitHub (pode ser `pareceres-validacao`).
2. Aponte o remote e envie:

   ```bash
   git remote add origin https://github.com/SEU-USUARIO/pareceres-validacao.git
   git branch -M main
   git push -u origin main
   ```

3. No repositório: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `/ (root)` → Save**.
4. Em ~1 minuto o site fica em:
   `https://SEU-USUARIO.github.io/pareceres-validacao/`

O link é público — qualquer pessoa com o endereço abre, sem conta.
A tag `noindex` no `index.html` pede aos buscadores que não indexem a página, mas
**não** a torna privada.

## Atualizar depois

Substitua o `index.html` e faça um novo commit:

```bash
git add index.html && git commit -m "atualiza pareceres" && git push
```

## Dados

Todos os pareceres são **exemplos**, com colaborador fictício (João da Silva
Santos) e fornecedor fictício (Fornecedor Exemplo Ltda). Não há dado real de
cliente ou colaborador.
