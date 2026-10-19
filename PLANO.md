# PLANO — Vendas com IA 4 · Do Zero ao Primeiro Cliente (v7.2)

Curso 4 de 5 da Formação Vendas com IA (ordem sugerida 1 → 3 → 2 → **4** → 5). Papel do Profissional 2030: **Auditor** como porta de entrada, depois **Consultor**. Base comum: riscos de IA (aula 3 e 8), LGPD e escopo com autorização por escrito (aula 3), relatório de uma página para executivo (aula 3 e 8).

Visão: construir ficou fácil, confiar não. A auditoria de IA abre a porta da empresa e é a ponte para a formação Auditor do Profissional 2030. Ofertas que eram só "construir site, loja ou robô" aparecem como as que perdem valor; a construção entra como parte de um serviço de confiança (diagnosticar, revisar, acompanhar, ensinar).

Fonte (não alterada): `~/projetos/formacao-vendas-ia-primeiro-cliente` (COURSE_PLAN.md e `curso/trilha*/modulo-*.html`). Ângulo do Auditor: `~/projetos/ia-2027/estrategia/CURRICULO-PROF2030.md` §4 e §7. Regras: sem promessa de renda; dólar só como faixa ilustrativa com "adapte ao seu mercado"; sem citar a fonte original; nada inventado (a ligação simulada é ficção rotulada; o que ela ensina vem da fonte 3.2).

Empresa-laboratório dos exercícios: **Horizonte Distribuidora** (`https://inematds.github.io/prof2030-lab/`), PME fictícia de 40 pessoas. Aqui o aluno só faz o inventário, nomeia riscos e escreve autorização e plano; achar as falhas plantadas é trabalho da formação Auditor.

## As 8 aulas

| # | slug | aula | objetivo | diagrama | prática ("pronto quando") | fonte |
|---|---|---|---|---|---|---|
| 1 | `piramide` | O que perde valor e o que fica | separar as ofertas de construção, que perdem valor, das de confiança, que se acumulam, e montar o seu portfólio de 4 ofertas | pirâmide (escada): construção no topo → revisão → acompanhamento → diagnóstico e ensino na base | portfólio de 4 ofertas com o que fica de fora, a sequência e a conta de margem; nenhuma oferta é só "eu construo" | 1.1 |
| 2 | `nicho` | Ondas, confiança e nicho | escolher um nicho pelos 3 critérios e começar pelo sim fácil que gera confiança | onda: novidade → primeiras → maioria atrasada (a janela) → todo mundo; e sim fácil → presença → problema grande → prova | tabela de nichos com notas nos 3 critérios, vencedor e frase de posicionamento que cabe num fôlego | 1.2 |
| 3 | `auditoria` | A auditoria de IA em 4 passos | conduzir uma auditoria de IA com autorização escrita, inventário, riscos e relatório com plano de 30 dias | autorização → pesquisar → inventariar → riscos e soluções → relatório | termo de escopo e autorização preenchido; inventário da Horizonte com as peças e o dono de cada uma; plano de 30 dias | 2.1 + CURRICULO §4 |
| 4 | `preco` | Preço é teste | montar a sua tabela de preços por faixa, com a conta do valor e a separação manutenção × melhoria | proposta → resposta do mercado → ajuste (laço) | tabela com 5 serviços (inclui, não inclui, prazo, preço de lançamento) e a frase do preço em menos de 15 s | 2.2 |
| 5 | `lista` | Lista que converte | montar uma lista qualificada de empresas e a rotina diária de contato | mapa → 3 peneiras → nome de quem decide → planilha de cores → rotina | planilha com 20 empresas qualificadas, nome de quem decide e cor; regras de contato do seu país anotadas | 3.1 |
| 6 | `ligacao` | Ligação fria com permissão | ligar pedindo permissão, falar de resultado e marcar a reunião sem explicar o serviço | permissão (15 s) → pitch de uma frase → segurar a informação → dois horários → convite | roteiro de uma página do seu nicho; ligação simulada com placar máximo | 3.2 · **simconversa** |
| 7 | `reuniao` | Da reunião marcada à fechada | preparar a prévia do diagnóstico com dados públicos e conduzir 15 minutos ouvindo mais do que falando | confirmar → prévia do diagnóstico → 4 abas → calibrar → ouvir e mostrar → oferta de entrada | mensagem de confirmação pronta; roteiro de 15 min em que a sua fala soma até 7 min | 4.1 |
| 8 | `entrega` | Entregar, acompanhar e o plano de 30 dias | entregar rápido nas contas do cliente, revisar o agente pelas 5 partes e montar o plano de 30 dias até o 1º cliente | ciclo: entrega → acompanhamento quinzenal → problema seguinte → depoimento → próximo cliente | checklist de revisão do agente de WhatsApp da Horizonte com 3 correções; plano datado pelo gerador (.md + .ics) | 4.2 |

A aula 8 fecha com `mapa` (4 degraus: auditar, precificar, prospectar, entregar) + `gerador` (plano com os exercícios das 8 aulas).

## O ângulo 2030 (onde cada ponto aparece)
- Inventário de apps e agentes: aula 3 (passo inventariar + exercício na Horizonte).
- Riscos de dados, permissões e chaves: aula 3 (passo riscos) e aula 8 (revisão do agente).
- **Autorização por escrito**: aula 3 (passo 0 e modelo "Termo de escopo e autorização").
- Escopo dito em voz alta: "não é pentest, nem resposta a incidente, nem parecer jurídico" (aula 3, no termo e na abertura da reunião; aula 7).
- Relatório com plano de 30 dias: aula 3 (entregável) e aula 8 (mapa).
- Ponte: aula 3 e aula 8 apontam para a formação Auditor (`https://eventos.inema.pro/prof2030/`).

## A simconversa da aula 6 — "o dono da distribuidora"

Personagem (ficção rotulada): Carlos, dono de uma distribuidora de 40 pessoas, atende o próprio celular no meio do expediente. Melhor caminho = 12 pontos.

| fala | cliente | opções (nota → destino) |
|---|---|---|
| `recepcao` | "Distribuidora, bom dia. Com quem quer falar?" | "o responsável" (0 → `fim-barrado`) · "O Carlos está?" (2 → `sobre`) |
| `sobre` | "Ele está esperando? É sobre o quê?" | honestidade: ligação fria + uma frase (2 → `abre`) · "assunto pessoal" (0 → `fim-barrado`) · explicar a auditoria à recepção (1 → `abre`) |
| `abre` | "Alô, Carlos falando." | nome + "ligação fria, me dá 15 segundos ou prefere desligar?" (2 → `permissao`) · "tem um minutinho?" (1 → `permissao`) · apresentar a consultoria (0 → `fim-desliga`) |
| `permissao` | "Fala, 15 segundos." | explicar auditoria, inventário, OWASP… (0 → `fim-desliga`) · pitch: resultado + negar a suposição (2 → `curioso`) · "a gente faz IA para empresas" (1 → `curioso`) |
| `curioso` | "Como assim? O que exatamente vocês fazem?" | explicar o método (0 → `fim-email`) · "o melhor é ver; 15 min para mostrar, faz sentido?" (2 → `horario`) · mandar material por e-mail (1 → `fim-email`) |
| `horario` | "Faz. Me liga semana que vem." | "quando for bom para você" (0 → `fim-email`) · "hoje às 16h ou amanhã às 10h?" (2 → `fim-bom`) · "terça que vem às 10h?" (1 → `fim-longe`) |

Fins: `fim-barrado` (sem nome, parou na recepção), `fim-desliga` (sem permissão, tudo é ruído), `fim-longe` (marcou, mas uma semana depois), `fim-email` ("manda por e-mail" quase sempre é não: azul na planilha, volta em uma semana), `fim-bom` (horário marcado, convite antes do próximo número). Lição: a ligação vende a reunião, não o serviço.

## Decisões
- A tabela "como se monta um mês inteiro" (com total em dólar) da fonte 1.1 ficou de fora: soa como promessa de renda. Fica só o mecanismo (auditoria puxa correção, que puxa treinamento, que puxa acompanhamento).
- O percurso de preço por hora da fonte 2.2 (valores do diagrama) não entra: os números não estão no texto da fonte.
- A "primeira venda = robô de conversa no site" (fonte 1.2) vira o exemplo da oferta que perde valor; a entrada passa a ser a auditoria de IA, e o robô entra como correção dentro dela.
- A "demonstração montada antes de receber" (fonte 4.1) vira a prévia do diagnóstico com dados públicos: mostrar, não contar.
- As 5 partes da instrução do agente (fonte 4.2) viram checklist de revisão; a parte SEGURANÇA é o centro.
- Objeções e fechamento ficam em uma linha com ponteiro (donos: cursos 3 e 5); call de descoberta, no curso 2.
- Números do mercado (Gartner etc.) do CURRICULO §4 não entram.
