![Pronto Saúde Digital|100x397,20%](https://i.imgur.com/ufUaJO5.png)

# Backend Developer Challenge
Este é um desafio simples para testar suas habilidades full stack na construção de páginas web.
Os serviços da Pronto Saúde Digital usam majoritariamente as tecnologias de Vue.js para o frontend e Node.js para o backend.

# O Desafio
Crie uma página em vue.js simples para realizar o agendamento de consultas. Esta página deve:
- Coletar a lista de espacilidades realizando o fech em uma api fictícia.
- Editar um cliente
- Obter um cliente específico
- Listar clientes

Um Cliente deve ter os seguintes campos:
- nome
- data de nascimento
- sexo 
- [ problemas de saude ]
- data de criação
- data de atualização

Problemas de Saúde
- nome
- grau do problema (de 1 a 2)
    
    ```
    ex: diabetes, grau 2
    ```

Criar um endpoint para trazer os 10 clientes com maior risco de saúde, no qual o cálculo é:
    
    ```
        sd = soma do grau dos problemas
        score = (1 / (1 + eˆ-(-2.8 + sd ))) * 100
    ```

# Requisitos
- Todas as respostas da API devem ser JSON
- Fornece um arquivo README.md com instruções de uso (como executar, endpoints etc)

# Recomendações
- Tests, tests and tests
- SOLID
- Código e commits em inglês (métodos, classes, variáveis, etc)

# Avaliação
- Estrutura, arquitetura e organização do projeto
- Boas práticas de programação
- Alcance dos objetivos propostos.

# Entrega
Você deve fazer um fork deste repositório e confirmar a solução na pasta de dev. Seu repositório deve ser público.

Enviar um e-mail para tech@olisaude.com.br com a url da sua solução.
