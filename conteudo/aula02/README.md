# Princípios SOLID
- **SOLID:** Acrônimo para 5 princípios de design de software
- **Objetivo:** _“Combater os problemas de um software mal projetado”_, como:
  - Alta rigidez: difícil de fazer alterações
  - Fragilidade: quebra em vários lugares a cada mudança
  - Baixa reutilização: módulos com alto acoplamento

| Inicial | Nome | Conceito |
| ------ | ---- | ---- |
| S | Single Responsability | Responsabilidade Única
|O | Open/Closed | Aberto/Fechado
|L |Liskov Substitution |Substituição de Liskov
|I |Interface Segregation |Segregação de Interfaces
|D| Dependency Inversion |Inversão de Dependência

## Single Responsability – Responsabilidade Única
**“_Uma classe deve ter um, e somente um, motivo para ser modificada._”**
- Uma classe deve ter apenas uma ou pouca responsabilidade
- Mantem o controle de operações realizados por uma classe
- Uma classe com muitas operações distintas não é o ideal

## Open/Closed - Princípio Aberto/Fechado
**_“Entidades de software (classes, módulos, funções) devem estar abertas para extensão (herança), mas fechadas para modificação.”_**
- Você deve ser capaz de adicionar novas funcionalidades sem alterar o código-fonte já existente
- Usar interface (classe abstrata) para que os métodos definidos nela possam ser herdados por outras classes e modificados via polimorfismo

## Liskov Substitution - Substituição de Liskov
**_“Classes-Filhas devem ser substituíveis por sua Classe-Pai sem quebrar a aplicação._”**

## Interface Segregation - Segregação de Interfaces
**_“Uma classe não deve ser forçada a implementar interfaces e métodos que não irá utilizar.”_**
- Em outras palavras, é melhor ter várias interfaces pequenas e específicas do que uma única interface grande e genérica.

## Dependency Inversion - Inversão de Dependência
**_“Módulos de alto nível não devem depender de módulos de baixo nível. Ambos devem depender de abstrações.”_**
- Sua classe não deve depender de uma implementação concreta de outra classe, mas sim de uma interface (abstração)
