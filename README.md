# Pareceres · Validação de Documentos

Catálogo dos critérios de **58 agentes de validação** de documentos: 31 do colaborador e
27 do fornecedor. Cada painel mostra o que o agente confere, o que reprova, o que é só
informativo e, quando existe, o que muda na versão customizada para uma construtora.

Página única e autocontida: CSS, script e a fonte Roboto ficam dentro do `index.html`.
Não há arquivo externo, e a página abre igual em qualquer navegador, sem depender de rede.

## Grupos

| grupo | agentes |
|---|---|
| Colaborador · Documento único | 18 |
| Colaborador · Treinamentos NR | 7 |
| Colaborador · Fluxos unificados | 6 |
| Fornecedor · Documento único | 17 |
| Fornecedor · Folha e cruzamentos | 3 |
| Fornecedor · Fluxos unificados e suas peças | 7 |

Além dos agentes, há quatro painéis de leitura: início com busca, como ler um parecer,
erros técnicos e padrão × customizado.

## Como navegar

- Barra no topo: índice, anterior, próximo e a lista de painéis.
- Teclado: `←` e `→` trocam de painel; `Home` volta ao índice.
- Link direto para um agente: `…/pareceres-validacao/#c01-aso`, por exemplo.
- Impressão: cada painel sai numa página, com todas as versões customizadas.

## Publicar no GitHub Pages

Settings → Pages → Source: Deploy from a branch → Branch: `main` / `/ (root)` → Save.
O site fica em `https://SEU-USUARIO.github.io/pareceres-validacao/`.

O link é público. A tag `noindex` pede aos buscadores que não indexem a página, mas não a
torna privada. O site não identifica clientes: as customizações aparecem como
"Customizado A", "B", "C".

## Atualizar depois

O `index.html` é gerado a partir dos catálogos de critérios, que ficam fora do repositório.
Não edite o HTML à mão: gere de novo e substitua o arquivo.

```bash
git add index.html && git commit -m "atualiza pareceres" && git push
```
