# Pareceres · Análise da IA do GD4

Catálogo dos critérios que a **IA do GD4** usa para sugerir a aprovação ou a reprovação de
**69 documentos**: 36 do colaborador e 33 do fornecedor. Cada documento segue o formato da
janela "Análise da IA" do GD4: os critérios da análise, o critério e a orientação de cada item,
o nome com que ele aparece no GD4 e, quando existe, o que muda na versão customizada de uma
construtora.

Página única e autocontida: CSS, script e a fonte Roboto ficam dentro do `index.html`.
Não há arquivo externo, e a página abre igual em qualquer navegador, sem depender de rede.

## Grupos

| grupo | documentos |
|---|---|
| Colaborador · Documentos únicos | 15 |
| Colaborador · Documentos com cruzamento | 6 |
| Colaborador · Segurança do trabalho | 15 |
| Fornecedor · Documentos únicos | 12 |
| Fornecedor · Documentos com cruzamento | 16 |
| Fornecedor · Segurança do trabalho | 5 |

Além dos documentos, há três páginas de apoio: início com busca, como ler a análise da IA e
mensagens de erro técnico.

## Como navegar

- Barra no topo: índice, anterior, próximo e a lista de painéis.
- Teclado: `←` e `→` trocam de painel; `Home` volta ao índice.
- Link direto para um documento: `…/pareceres-validacao/#c15-cartao-ponto`, por exemplo.
- Impressão: cada documento sai numa página, com as regras completas e todas as versões customizadas abertas.

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
