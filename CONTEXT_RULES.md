# Regras de Governança de Contexto da IA

## 1. Objetivo
Orientar a geração e a revisão do código do sistema TaskAnalyzer.

## 2. Tecnologias obrigatórias
- Utilizar Python 3.11 ou superior.
- Utilizar pytest para os testes automatizados.
- Utilizar type hints em todas as funções e parâmetros.

## 3. Regras de implementação
- Implementar a função analyze_tasks.
- Implementar a exceção personalizada TaskValidationError.
- Validar os dados de entrada antes de realizar os cálculos.
- Rejeitar tarefas cuja data de conclusão seja anterior à data de criação.
- Evitar divisão por zero.
- Retornar 0.0 para médias quando não houver tarefas concluídas.
- Tratar entradas vazias e tarefas pendentes sem erros não tratados.

## 4. Indicadores obrigatórios
- Total de tarefas.
- Total de tarefas concluídas.
- Total de tarefas pendentes.
- Tempo médio de conclusão em horas, geral e por prioridade.
- Taxa de atraso percentual.

## 5. Regras para uso da IA
- Não inventar requisitos que não estejam documentados.
- Informar ambiguidades antes de assumir regras de negócio.
- Não adicionar dependências sem necessidade justificada.
- Gerar código legível, organizado e testável.
- Conferir a implementação com os testes automatizados.
- Não considerar o código aprovado sem executar os testes.

## 6. Validação humana
O código gerado pela IA deve ser revisado por uma pessoa.
A revisão deve verificar os requisitos, os cálculos, as
validações e os resultados dos testes.

## 7. Limitação
Este documento foi reconstruído com base no enunciado da
Fase 2 e não substitui a versão original da Fase 1.
