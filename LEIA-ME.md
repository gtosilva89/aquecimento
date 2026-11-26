# 🎪 Feira de Ciências: aquecimento (Técnico em IA, turma 202600029, 26/11/2026)

Atividade com **apresentação** (projetor) e **jogo** para aquecer para as avaliações de **sexta 27/11 (Python, ind. 3 e 4)**, **sábado 28/11 (Banco de dados, ind. 4, 5 e 6)** e **03 e 04/12 (Redes/GPU, ind. 4 e 5)**.

Link (depois de ativar o GitHub Pages): https://gtosilva89.github.io/aquecimento/

## Como funciona
- **Apresentação** (botão 📽️): 13 slides com missão, regras de XP, "Relembrando" (exemplos diferentes do jogo), onde consultar no LMS, placar ao vivo e correção (estes dois pedem a senha). Teclas: ← → passa, N notas do professor, F tela cheia, Esc sai.
- **Jogo**: o aluno entra com o nome completo. Estande 1 (10 perguntas de Python), Estande 2 (10 de Banco de dados), Estande 3 (10 de Redes) e Estande 4, o Desafio do Júri (caça aos erros e 6 respostas digitadas, com X = número pessoal do aluno, sem colar). XP, combo, medalhas, níveis e conquistas. Botão 📖 Consultar com resumo e o lugar no LMS.
- **A, PA e NA** por indicador: A = 70% ou mais dos pontos, PA = 50% a 69%, NA = menos de 50%. O aluno vê no fim; o professor vê na Área do professor e no Excel.
- **Respostas no repositório**: cada aluno grava `respostas/<código>.json` (no fim de cada estande, na entrega e a cada 8 minutos). O conteúdo vai **cifrado**: só a senha do professor abre. Nada fica guardado no navegador do aluno (só enquanto a aba está aberta, para não perder se recarregar).
- **Área do professor** (🔒, senha a mesma do Arquipélago Byte): lê a pasta `respostas/`, mostra a tabela com A/PA/NA, resumo da turma, perguntas mais erradas e as respostas de cada aluno ao lado do modelo. O botão 📊 gera o **Excel com senha** (`respostas/Aquecimento_Feira_26-11_respostas.xlsx`), salva no repositório e baixa.

## Antes da aula (uma vez)
1. Settings → Pages → Branch **main** / **root** → Save.
2. Criar a chave de envio (token): https://github.com/settings/personal-access-tokens/new → Only select repositories: **aquecimento** → Contents: **Read and write** → expiração 31/12/2026.
3. Abrir o site → 🔒 Área do professor → 🔑 Chave de envio → colar o token → "Testar e guardar". Copiar o **link para os alunos** (ele já leva a chave) e mandar pelo LMS/Teams.

O código-fonte (com as respostas modelo) fica no repositório senac-docente, em `TURMAS/202600029.../aquecimento-2026-11-26/jogo-feira-de-ciencias/fonte` (`node build.js` gera o index.html). `xlsx-populate.min.js` é a biblioteca que monta o Excel com senha (licença MIT em LICENSE-xlsx-populate).
