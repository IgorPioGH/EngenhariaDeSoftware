### Determinação de um cronograma
- Envolve diferentes abordagens dependendo do prazo

### Precisão nos cronogramas
- Pode ser mais importante do que a precisão nos custos
- Atraso no cronograma podem gerar insatisfação do cliente e problemas de integração

### Atividades no Cronograma
- Como relacionar o tempo cronológico com o esforço humano
- Paralelismo e interdependência de tarefas
- Marcos de progresso
- Métodos de rastreamento

### Elaboração do Cronograma
- Tarefas essenciais:
	1. Identificar e selecionar os recursos para um projeto
	2. Inter-relacionar as atividades e definir precedências
	3. Calcular caminho crítico
	4. Alocar recursos nas atividades

#### Identificar e selecionar recursos para um projeto
- Recursos humanos, materiais de consumo e equipamentos, recursos financeiros
#### Inter-relacionar as atividades e definir precedências
- Rede PERT:
	- ![[Pasted image 20240930143635.png]]
#### Calcular Caminho Crítico
- Caminho Crítico é o mais longo no calendário através do cronograma
- Tempo mínimo de conclusão do projeto é a duração total do caminho crítico
- Caminho crítico apresenta o maior risco no cronograma
- Para diminuir o cronograma completo, é o caminho crítico que deve ser encurtado
#### Alocar recursos nas atividades
__Tarefa demorada, mas é base de todo o cálculo do orçamento__
- Como o esforço é alocado durante o processo de engenharia de Software:
	- *Planejamento* raramente é responsável por mais do que 2 a 3% do esforço total
	- *Análise de Requisitos* pode envolver de 10 a 25% do esforço do projeto (Se houver a necessidade de construir protótipos a porcentagem aumenta proporcionalmente)
	- *Projeto de Software* normalmente é aplicado uma margem de 20 a 25% do esforço
		- *Revisão* não deve ser ignorado
	- *Código* de 15 a 20%, por conta do esforço aplicado no *projeto de software* o esforço necessário no código não é tão grande
	- *Teste e depuração* 30 a 40% de esforço

#### Preparar o cronograma completo
- Representar graficamente as datas de início e término de cada atividade
- Ocorre quando os recursos, durações e interdependências já estão estabelecidos
- Gráfico de _Gantt_

### Prazos diferentes
#### Caso 1
- O cliente não impôs prazo para o término
	1. Determinar o Caminho Crítico
	2. A duração total do caminho crítico é o tempo mínimo possível para cumprir o cronograma
	3. Elaborar o cronograma considerando-se todas as atividades da rede com suas durações normais

#### Caso 2
- O cliente impôs um prazo maior do que o estimado para o término do projeto
	1. Reestudar as atividades para tentar economizar em implementação ao realizar atividades em ritmo mais lento
	2. Produzir uma tabela com o custo normal e com o custo com ritmo mais lento
	3. Refazer a rede de acordo com as novas durações das tarefas
	4. Elaborar o Cronograma considerando-se as novas durações das atividades

#### Caso 3
- O cliente impôs um prazo menor do que o estimado para o término do projeto
	- Mesmos passos do Caso 2, mas a tabela é com as atividades em ritmo acelerado