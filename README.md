# Programação Web - Aula 2

Repositório com os exercícios desenvolvidos na **Aula 2** da disciplina de Programação Web do curso Técnico em Informática.

## Descrição da Aula
Nesta aula foram estudados os conceitos básicos de **Lógica de Programação** e **Introdução ao JavaScript**, com foco em:
- Variáveis
- Entrada e saída de dados
- Estruturas condicionais (if/else)
- Manipulação do DOM
- Interação com o usuário através de botões

## Projetos Desenvolvidos

### 1. Verificador de Situação Eleitoral

**Arquivo:** `situacao-eleitoral.html`

**Funcionalidades:**
- Lê nome e idade do usuário através de campos de formulário
- Utiliza estruturas condicionais (`if`, `else if`) para determinar a situação eleitoral conforme a legislação brasileira
- Validação de campos obrigatórios
- Exibe o resultado diretamente na página
- Possui botão para limpar os campos

**Regras aplicadas:**
- Menor que 16 anos → Não pode votar
- 16 a 17 anos → Voto facultativo
- 18 a 70 anos → Voto obrigatório
- Acima de 70 anos → Voto facultativo

### 2. Cadastro de Aluno

**Arquivo:** `cadastro-aluno.html`

**Funcionalidades:**
- Cadastro de aluno com nome, idade e nota final
- Cálculo automático da situação do aluno (Aprovado, Recuperação ou Reprovado)
- Validações completas de entrada de dados
- Exibição do resultado com cores diferentes conforme a situação:
  - Verde para Aprovado
  - Amarelo para Recuperação
  - Vermelho para Reprovado
- Interface com botões para cadastrar e limpar campos

**Critérios de aprovação:**
- Nota ≥ 7.0 → Aprovado
- Nota entre 5.0 e 6.9 → Recuperação
- Nota < 5.0 → Reprovado

## Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript (Vanilla)

## Como executar os projetos
1. Baixe os arquivos
2. Abra qualquer um dos arquivos `.html` diretamente no navegador
3. Preencha os campos e clique em "Cadastrar Aluno" ou "Verificar Situação"

---

**Aluno:** Jaime  
**Disciplina:** Programação Web  
**Curso:** Técnico em Informática