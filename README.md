# Funil da Turma

Mini-CRM de vendas para o curso Técnico em Vendas, alinhado às pautas formativas 2 a 6 do Multiplica SP. Os grupos prospectam comércios reais, qualificam com BANT, criam roteiros de abordagem, treinam negociação e acompanham tudo num painel da turma.

**No ar:** https://funildaturma.vercel.app

## Como usar em aula

1. **Crie a sala.** Abra `https://funildaturma.vercel.app/?sala=CODIGO` com um código da turma (letras minúsculas, números e hífen, de 3 a 40 caracteres), por exemplo `?sala=2em-vendas`.
2. **Defina a senha da professora primeiro.** No Painel, em "Modo professora", digite uma senha (mínimo 4 caracteres). A primeira senha usada numa sala vira a senha dela.
3. **Renomeie os grupos** (só no modo professora).
4. **Mande o link com o código da sala aos alunos.** Cada grupo escolhe seu nome no topo da página.
5. **Teste inicial:** cada grupo responde a aba "Teste antes/depois" com a opção "Antes".
6. **Sequência:** Leads (P2) → Qualificar (P6) → Roteiro (P3/P5) → Negociação (P4).
7. **Teste final:** repetir o teste com a opção "Depois".
8. **Evidências:** no Painel, use "Copiar resumo" e "Baixar planilha (CSV)" para a socialização.

## O que fica salvo

Os dados ficam no Supabase, separados por código de sala: leads com a linha do tempo das etapas, notas BANT, melhor nota no simulador, teste antes/depois e nomes dos grupos. Só a professora (com a senha) pode remover leads e renomear grupos.

Não cadastre dados pessoais (CPF, telefone pessoal). Use só informações públicas dos comércios.
