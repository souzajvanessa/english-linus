# english-linus

Plataformas interativas de revisão de Língua Inglesa — Prof.ª Vanessa.

Três atividades em HTML puro: abrem no navegador, funcionam no celular, **não precisam de internet depois de carregar** e não coletam nenhum dado dos alunos.

## O que tem aqui

| Pasta | Atividade | Turma | Conteúdo |
|---|---|---|---|
| `1ano/english-plus/` | **ENGLISH+** | 1º ano A – EM | 13 episódios: vocabulário de cinema, séries, música e eventos; WH questions; simple present; present continuous; pronomes; 3 textos; quiz final em 3 níveis |
| `1ano/rewind/` | **ENGLISH REWIND** | 1º ano A – EM | Revisão dos Chapters 1 a 5: verb BE, pronomes, possessivos, reflexivos, present continuous, so/yet, time idioms |
| `8ano/chefs-table/` | **CHEF'S TABLE** | 8º ano | 10 estações: vocabulário de cozinha, countable/uncountable, how much/how many, quantidades e preços, food allergies, jogo de pares, forca do soufflé, would you rather, reading |
| `pdf/` | Folhas do aluno | — | Versões para imprimir, em PDF |

Página inicial: **`index.html`** na raiz.

## Endereços das páginas

Depois de ativar o GitHub Pages, os links ficam assim (troque `souzajvanessa`):

```
https://souzajvanessa.github.io/english-linus/                    → página inicial
https://souzajvanessa.github.io/english-linus/1ano/english-plus/  → ENGLISH+
https://souzajvanessa.github.io/english-linus/1ano/rewind/        → ENGLISH REWIND
https://souzajvanessa.github.io/english-linus/8ano/chefs-table/   → CHEF'S TABLE
```

## Como publicar (primeira vez)

1. Crie uma conta em **github.com** (gratuita).
2. **New repository** → nome `english-linus` → **Public** → *Create repository*.
3. Na página do repositório: **Add file → Upload files**. Arraste **todo o conteúdo desta pasta** (inclusive as subpastas `1ano`, `8ano` e `pdf`). Escreva qualquer coisa em *Commit changes* e confirme.
4. **Settings → Pages** → em *Source*, escolha **Deploy from a branch** → Branch: **main**, pasta **/ (root)** → *Save*.
5. Espere de 1 a 3 minutos e recarregue a página de Settings → Pages. O endereço aparece no alto.

## Como atualizar depois

**Add file → Upload files**, arraste o arquivo novo com o mesmo nome e confirme. O site atualiza em cerca de um minuto. Se não mudar, dê `Ctrl + Shift + R` no navegador para limpar o cache.

## Como adicionar uma atividade nova

Estrutura fixa: **`turma / nome-da-atividade / index.html`**

1. Crie a pasta da atividade dentro da pasta da turma e coloque o arquivo lá, renomeado como `index.html`.
2. Abra o `index.html` da **raiz** e acrescente um bloco na lista `ATIVIDADES`, que está no alto do arquivo, dentro da área marcada como editável. Copie um bloco existente e troque os campos.
3. Dê duplo clique no `index.html` da raiz para conferir se o cartão apareceu.
4. Suba a pasta nova **e** o `index.html` da raiz.

Turmas já configuradas na lista `TURMAS`: `4ano`, `5ano`, `8ano`, `9ano`, `1ano`. As seções aparecem no site na ordem dessa lista, e turma sem atividade não aparece.

## Regras da pasta

- O arquivo principal de cada atividade **precisa** se chamar `index.html` — é isso que gera o link curto e bonito.
- Não apague o arquivo `.nojekyll`. Ele impede o GitHub de tentar processar as páginas e quebrar o layout.
- Nomes de pasta e arquivo: **sem espaços, sem acentos, tudo minúsculo, separados por hífen**.
- Nunca edite o cartão direto no HTML: a página inicial monta os cartões sozinha a partir da lista `ATIVIDADES`. Mexer só ali evita quebrar o layout.

## ⚠️ O que NUNCA subir aqui

Este repositório é **público**. Não coloque nesta pasta:

- gabaritos, planos de aula ou qualquer material com respostas;
- notas, listas de presença, nomes ou qualquer dado de aluno;
- páginas escaneadas do livro didático (material protegido por direito autoral).

As respostas das atividades ficam dentro do código dos arquivos HTML — um aluno curioso consegue vê-las abrindo o código-fonte da página. Isso vale para qualquer quiz que roda no navegador. Para atividade valendo nota, use a folha impressa.
