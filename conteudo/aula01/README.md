# Modelo C4
- **Um tipo de modelagem de software**
- **Visa criar mapas do software em vários níveis de detalhe (de 1 a 4)**

## Níveis de mapeamento (Diagramas)
- **Contexto:** Mostra o sistema e suas interações com **usuários** e **sistemas externos**
- **Container:** Mostra detalhes dos principais containers do sistema (front-end, back-end, API, banco de dados, etc)
- **Componentes:** Detalha os componentes lógicos (software) dentro de um container e suas interações
- **Código:** Detalha a implementação do componente

## Detalhes dos diagramas
### Contexto
<img width="735" height="372" alt="image" src="https://github.com/user-attachments/assets/4593f39d-0966-4d7e-8881-8073b6198d55" />


### Container
<img width="773" height="392" alt="image" src="https://github.com/user-attachments/assets/7214f032-d393-4dd6-ba43-4ca4670fd43a" />

### Componentes
<img width="793" height="402" alt="image" src="https://github.com/user-attachments/assets/9dd019ee-8f1b-4646-add2-5baa0271a2be" />


## Notação dos diagramas do C4
<img width="988" height="539" alt="image" src="https://github.com/user-attachments/assets/5f10159d-e5da-4a93-8f80-5392573c55eb" />

### Elementos
- **Os diagramas devem ter um título descrevendo o tipo e o escopo do programa**
- **O tipo de cada elemento do diagrama deve ser especificado e deve ter uma breve descrição**
  - [Person], [Software System], [Container], [Component]...
- **Cada container e componente deve ter uma tecnologia especificada explícita. Recomendado pôr as versões utilizadas**

### Relacionamentos
- **Cada ligação (seta) deve representar uma relação unidirecional e deve explicar sua função (relação) no contexto**
- **As relações entre containers devem ter uma tecnologia/protocolo explicitamente dito, que representam comunicação entre contextos**
