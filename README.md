![Pronto Saúde Digital|100x397,20%](https://i.imgur.com/ufUaJO5.png)

# Backend Developer Challenge
Este é um desafio simples para testar suas habilidades full stack na construção de páginas web.
Os serviços da Pronto Saúde Digital usam majoritariamente as tecnologias de Vue.js para o frontend e Node.js para o backend.

Para codificar nossa interface gráfica utilizamos como base um template adquirido que está disponível em https://github.com/ProntoSaude/modernize-template. Utilize os componentes disponibilizados lá para montar sua interface e realize as adaptações que julgar necessário.

Não se preocupe com os arquivos de estilo como logo e cores, nem com a formulação dos breadcrumbs e do menu do perfil, para este teste, utilize o padrão do template.

Também não se preocupe com a alocação dos arquivos nas pastas corretas, apenas entregue os arquivos .vue e .js que compõem sua solução.

# O Desafio
Crie uma página em vue.js simples para realizar avaliação de uma consulta. Esta página deve:
- Apresentar o resumo do perfil do profissional
- Coletar a avaliação do atendimento
- Coletar a avaliação da plataforma
- Coletar a avaliação do profissional

A seguir, são disponibilizadas imagens que servem como inspiração para elaboração da estrutura da sua página:

![Tela de avaliação|100x397,20%](https://i.imgur.com/B8ghWnF.png)
![Tela de avaliação|100x397,20%](https://i.imgur.com/X7eHCpM.png)

As informações coletadas devem ser enviadas para uma rota da API que irá desenvolver para salvar o registro da avaliação no banco de dados. Para isso, utilize a bibilioteca Axios. 

O ID da sessão a qual se refere a avaliação deverá ser obtido dinamicamente através da leitura do parâmetro "session" da URL da avaliação.

Considere que o ID do profissional e usuário, bem como demais informações necessárias foram fornecidos e estão em uma variável.

Não é necessário realizar requisições para coletar as informações de informações adicionais da página, de forma que elas podem estar no código de maneira "hardcoded".

# A API

Sua api deve conter apenas uma rota (nomeclatura livre) do tipo post e deve realizar a gravação das informações recebidas em um banco de dados MongoDB. Não é necessário provisionar a infraestrutura do banco de dados, apenas configure o schema e o processo de envio para o banco e deixe a URL preparada para receber seus dados de um arquivo .env.

Informações necessárias para gravação (pode utilizar valores aleatórios):

- ID do usuário que respondeu à pesquisa.
- ID do profissional que realizou a consulta
- ID da sessão da avaliação
- Array de objetos das avaliações contendo nota e comentários de cada aspecto avaliado.
- Habilite o timestamps pra cada registro.

# Requisitos
- Toda comunicação (envio e resposta) com a API devem ser feita utilizando JSON.
- Forneça um arquivo README.md com instruções de uso (como executar, endpoints etc)

# Recomendações
- Código em português (métodos, classes, variáveis, etc)

# Avaliação
- Boas práticas de programação.
- Alcance dos objetivos propostos.

# Entrega
Você deve realizar o envio dos arquivos para rambo@prontosaude.digital
