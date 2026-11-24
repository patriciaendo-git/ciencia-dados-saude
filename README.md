# Ciência de Dados na Saúde · PPGEnf UPE/UEPB

Site da disciplina Ciência de Dados na Saúde (mestrado e doutorado, 45 h), da Profa. Patricia Takako Endo e da Profa. Danielle Moura, com o dotLAB · Grupo de Pesquisa em Transformação Digital (UPE).

## Estrutura

- `index.html` · página da disciplina: fio condutor, encontros, materiais de apoio, protótipo da turma e entregas
- `materiais/ficha-do-problema.html` · ficha para levantar problemas (encontros 1 a 3)
- `materiais/cardapio-de-solucoes.html` · tipos de solução tecnológica que não são IA (encontro 1)
- `materiais/matriz-de-priorizacao.html` · matriz interativa para escolher o problema (encontro 4)
- `upe.png`, `fensg.png` e `logo.png` · logos da UPE, da FENSG e do dotLAB
- `encontros/<pasta>/` · materiais de cada encontro, quando forem publicados

## Publicar um material

Na lista `ENCONTROS` do `index.html`, preencha dentro do encontro:

- slides ou material de estudo: `{arq:"encontros/<pasta>/<arquivo>.pdf", pag:14, ver:"Versão 1.0 · mês de ano"}`
- página interativa: `{pagina:"encontros/<pasta>/index.html", ver:"Versão 1.0 · mês de ano"}`

Material sem arquivo aparece como "Em preparação"; `null` esconde o item.

## GitHub Pages

Settings → Pages → Deploy from a branch → `main` / `(root)`.
