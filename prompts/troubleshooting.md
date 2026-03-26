# ⚠️ Troubleshooting / Cicatrizes do Processo

## Desafio 1 — Respostas amplas demais
**Problema:**  
Algumas respostas iniciais do NotebookLM ficaram muito genéricas e explicavam a AWS de forma ampla demais, sem foco direto na certificação.

**Solução adotada:**  
Os prompts foram refinados com expressões como:

- “com foco em certificação”
- “com foco em prova”
- “de forma simples”
- “para iniciantes”
- “com foco em memorização”

---

## Desafio 2 — Confusão entre serviços parecidos
**Problema:**  
Serviços como EC2, Lambda e ECS, ou S3, EBS e EFS, podem parecer muito parecidos para quem está começando.

**Solução adotada:**  
Foi necessário mudar a estratégia e usar **prompts comparativos**, pedindo explicitamente:

- diferenças
- objetivo
- quando usar
- analogias simples

Isso melhorou bastante a retenção dos conceitos.

---

## Desafio 3 — Excesso de informação técnica
**Problema:**  
Em alguns momentos, a resposta vinha correta, mas muito “documentação oficial”, o que dificultava a revisão rápida.

**Solução adotada:**  
Os prompts passaram a pedir:

- linguagem simples
- resumos em tópicos
- glossários
- explicações curtas

---

## Desafio 4 — Dificuldade em separar ferramentas de custo
**Problema:**  
No início, houve confusão entre:

- AWS Pricing Calculator
- AWS Cost Explorer
- AWS Budgets

**Solução adotada:**  
Foi necessário pedir comparações específicas e focadas em:

- finalidade
- momento de uso
- diferença entre estimativa futura e análise histórica

---

## Desafio 5 — Necessidade de transformar teoria em revisão ativa
**Problema:**  
Ler explicações apenas em formato de resumo não era suficiente para fixar melhor o conteúdo.

**Solução adotada:**  
Foram utilizados prompts voltados para:

- criação de perguntas
- glossários
- checklist de revisão
- explicações em formato de comparação

---

## Aprendizado Final
A principal “cicatriz” deste processo foi perceber que **a qualidade da resposta depende diretamente da qualidade da pergunta**.

O NotebookLM se mostrou mais útil quando utilizado com:

- contexto claro
- objetivo definido
- foco no tipo de saída desejada
- refinamento contínuo dos prompts
