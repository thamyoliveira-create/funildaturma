# Funil da Turma

Mini-CRM de vendas para o curso Técnico em Vendas, alinhado às pautas formativas 2 a 6 do Multiplica SP. Os grupos prospectam comércios reais, qualificam com BANT, criam roteiros de abordagem, treinam negociação e acompanham tudo num painel da turma.

**No ar:** https://funildaturma.vercel.app

## Como usar em aula

1. **Crie a sala.** Abra `https://funildaturma.vercel.app/?sala=CODIGO` com um código da turma (letras minúsculas, números e hífen, de 3 a 40 caracteres), por exemplo `?sala=2em-vendas`.
2. **Entre como professora** com a senha de professora (a mesma para todas as salas). Os códigos dos grupos aparecem no Painel.
3. **Renomeie os grupos**, se quiser.
4. **Mande o link aos alunos e passe a cada grupo só o código dele.** O grupo escolhe o nome no topo, digita o código e vê só os próprios dados.
5. **Teste inicial:** cada grupo responde a aba "Teste antes/depois" com a opção "Antes".
6. **Sequência:** Leads (P2) → Qualificar (P6) → Roteiro (P3/P5) → Negociação (P4).
7. **Teste final:** repetir o teste com a opção "Depois".
8. **Evidências:** no Painel, use "Copiar resumo" e "Baixar planilha (CSV)" para a socialização.

## O que fica salvo

Os dados ficam no Supabase, separados por código de sala: leads com a linha do tempo das etapas, notas BANT, melhor nota no simulador, teste antes/depois e nomes dos grupos. Cada grupo acessa só os próprios leads e notas; o ranking mostra apenas os pontos. Só a professora vê tudo, remove leads, renomeia grupos e troca códigos.

Não cadastre dados pessoais (CPF, telefone pessoal). Use só informações públicas dos comércios.
