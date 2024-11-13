> # Relatório Criação de Sistema de Gerenciamento de Vendas e Estoque

![Logo ChocoArte](https://github.com/user-attachments/assets/8d7811ce-1830-4f3f-9342-89459bcb6ac8) Figura 1 - Logo Choco Arte

## Visão Geral
### O Desafio
Conceber e desenvolver um protótipo de software para automatizar e otimizar o processo de vendas e controle de estoque da empresa Chocoarte. 
O desafio central deste projeto é criar a prototipação do sistema de gerenciamento de vendas e estoque da Choco arte, que atualmente faz toda a gestão de forma manual. Há diversas melhorias que podem ser aplicadas ao método atual utilizado pela empresa, visando torná-lo mais eficiente para seus usuários e aumentando a produtividade e eficácia nas operações cotidianas. 
Neste cenário, é necessário:

- Análise de Steakholders: Identificar e entender as necessidades, expectativas, interesses e influência de cada stakeholder no desenvolvimento do projeto. 
- Levantar os Requisitos: Realizar o levantamento de quais requisitos funcionais e não funcionais são necessários para a criação do sistema dentro das necessidade da Choco Arte, garantindo que o sistema seja prototipado dentro das necessidades da empresa;
- Criar Prototipação: Uma vez que realizam toda a gestão de vendas e estoque de forma manual, a criação do protótipo é uma etapa de grande importância para o sistema. A partir dos requisitos levantados, a prototipação auxiliará o cliente a ter uma visão inicial das funcionalidades que estão disponíveis no sistema;


### Contexto
Atualmente, a Choco Arte não conta com um sistema digital para gestão de vendas e estoque, o que é feito manualmente, resultando em dificuldades no controle de entrada e saída de produtos, além de falhas no registro de vendas e na previsão de faturamento. 

## Why?
### Quem utilizará o sistema?
O sistema será utilizado exclusivamente pelos proprietários da Chocoarte, não sendo acessado diretamente pelos clientes.
#### Quais seriam os problemas?
Como a gestão das vendas e do estoque dos produtos acontece de forma manual, o controle das entradas e saídas fica dificultado e o processo de gerir a empresa fica mais moroso e maior possibilidade de erros.

### Storytelling
Em um dia típico na vida de Arthur, um jovem de 22 anos, da cidade de Teixeiras – MG, que estuda Análise e Desenvolvimento de Sistemas, o equilíbrio entre suas atividades diárias era um desafio constante. Além dos estudos, Raphael dedicava seu tempo à sua pequena empresa de doces, conciliando isso com sua paixão por esportes e lazer com a família, a namorada e os amigos, especialmente durante os jogos de vôlei nos finais de semana.

Arthur sempre foi um sonhador e seu objetivo era claro: criar uma empresa sólida, estruturada e bem-sucedida no futuro. No entanto, como microempreendedor, o caminho não era fácil, ele enfrentava inseguranças e medos frequentes. “E se eu estiver cometendo os erros ao empreender?”. A pressão de fazer as vendas funcionarem diariamente pesava em sua mente, especialmente em dias em que os resultados não eram bons.

A experiência de observar outros empreendedores o deixava dividido. Ele  percebia que muitas empresas estruturadas usavam sistemas para facilitar o trabalho e poupar tempo, enquanto outras, geralmente comandadas por pessoas mais velhas, ainda usavam métodos manuais, como cadernos para controle de estoque e contas.

Em uma tarde após a aula, Arthur estava mais determinado do que nunca a melhorar sua empresa. Ele sabia que a tecnologia poderia ser a chave, não só para seu sucesso, mas também para o crescimento de seu negócio de doces. No entanto, ele não podia ignorar os conselhos que ouvia constantemente: "Cuidado com suas decisões, nem sempre as coisas saem como planejado". Mesmo assim, sua visão era clara — ele queria ser bem-sucedido, dar prosseguimento na sua empresa para se tornar um pilar para seus pais, como forma de retribuição por tudo o que eles fizeram por ele.

Certo dia, em uma conversa com seu professor, Arthur decidiu compartilhar seus anseios e suas frustrações, o anseio de aprofundar no seu empreendimento, mas também os medos de errar e investir em algo que não desse certo, as incertezas quanto a aplicação de um sistema para um microempreendedor. O professor, ouvindo atentamente, respondeu: "Raphael, não se trata apenas do custo ou da complexidade. Trata-se de praticidade. A tecnologia, quando bem aplicada, facilita sua vida e faz com que você foque no que realmente importa."

Essas palavras marcaram Arthur. Ele percebeu que o segredo para superar suas inseguranças como empreendedor estava em buscar soluções que simplificassem suas operações. O próximo passo foi claro: ele precisaria implementar um sistema que não fosse apenas acessível, mas também simples e intuitivo para a gestão das vendas e do estoque.

Com essa nova motivação, Arthur começou a esboçar ideias das necessidades da sua empresa dentro de um sistema. Dentre os objetivos, o sistema idealizado por ele precisava ser prático e fácil de uso.

Com o tempo, Arthur começou a notar que sua visão de futuro estava se tornando mais clara e palpável. Ao adotar a tecnologia como aliada, ele não apenas simplificou a gestão de sua empresa, como também começou a crescer de forma consistente. Embora os medos e inseguranças ainda existissem, Raphael sabia que estava no caminho certo para alcançar seus objetivos — ser dono de uma empresa de sucesso e, ao mesmo tempo, ser um exemplo para seus pais e para as futuras gerações.

## Who - Análise dos Stakeholders
### Persona
![Brown and Cream Minimalist User Persona Poster (1)](https://github.com/user-attachments/assets/c0bea6ae-8d0f-48de-b58f-1abbf9a1c20c)

#### Mapa de Empatia
![Mapa de Empatia - Versão 1](https://github.com/user-attachments/assets/096d85f2-b82b-4f2d-a970-a83e0d3c3dd2)

## Engenharia de Requisitos

## Elicitação de Requisitos

Em reunião com o cliente, identificamos as principais necessidades que o sistema deverá atender. Elas incluem:

- Controle de estoque;
- Alerta de baixa estoque;
- Cadastro de produtos;
- Controle de caixa (fechamento de caixa, dentre outros);
- Emissão de notas.

## Especificação de Requisitos

A partir dos requisitos apresentados pelo cliente, a equipe responsável se reunião para elaborar os requisitos a nível de sistema que irá dar o suporte necessário para o desenvolvimento.

####   Requisito 1: Controle de Estoque

**ID:** REQ-002
 **Descrição:** O sistema deve permitir o acompanhamento em tempo real do inventário.

 **Detalhamento:**
- O usuário deve ser capaz de consultar a quantidade disponível de cada item no inventário.
- O sistema deve registrar a entrada e saída de produtos.
- Deve ser possível visualizar um histórico detalhado de movimentações, com capacidade de filtragem por:
- Data.
- Produto.
- Tipo de operação (entrada/saída).

**Justificativa:** Permite a gestão eficiente do inventário, evitando perdas e otimizando o controle dos produtos disponíveis.
 **Prioridade:** Alta

 #### Requisito 2: Alerta de Baixa de Estoque
 
**ID:** REQ-002
**Descrição:** O sistema deve emitir alertas automáticos quando o nível de estoque de qualquer produto atingir ou estiver abaixo de um valor mínimo definido.
 
 **Detalhamento:**
- O sistema deve permitir a configuração de valores mínimos de estoque por produto.
- O alerta deve ser enviado por e-mail e/ou exibido dentro do sistema.
- O sistema deve gerar relatórios com produtos que possuem estoque abaixo do mínimo definido.

**Justificativa:** Garantir a reposição de produtos e evitar rupturas de estoque.
**Prioridade:** Média

#### Requisito 3: Cadastro de Produtos

 **ID:** REQ-003
 **Descrição:** O sistema deve possibilitar o cadastro, consulta, edição e exclusão de produtos.

 **Detalhamento:**
As seguintes informações são obrigatórias no cadastro:
- Nome do produto.
- Código do produto (SKU ou outro identificador único).
- Descrição detalhada.
- Preço de venda e de custo.
- Unidade de medida (ex.: unidade, kg).
- Categoria e/ou subcategoria.
- Quantidade mínima em estoque para emissão de alerta de baixa.

**Justificativa:** Facilitar a organização e gestão dos produtos, garantindo que todos os dados necessários estejam disponíveis e atualizados.
**Prioridade:** Média

#### Requisito 4: Controle de Caixa

**ID:** REQ-004
**Descrição:** O sistema deve gerenciar as movimentações financeiras diárias.

 Detalhamento:
- Abertura de caixa com registro do valor inicial.
- Registro de todas as entradas e saídas financeiras (ex.: vendas, devoluções, despesas).
- Fechamento de caixa com cálculo automático do saldo final e geração de relatórios diários.
- Suporte para diferentes formas de pagamento (dinheiro, cartão, etc.).
- Relatório de fechamento de caixa, detalhando todas as movimentações do período.

 Justificativa: Facilitar o controle financeiro diário, assegurando a precisão dos registros e o controle das finanças.
 Prioridade: Alta
 
#### Requisito 5: Emissão de Notas Fiscais

**ID:** REQ-005
**Descrição:** O sistema deve emitir notas fiscais eletrônicas (NF-e) conforme a legislação vigente.

**Detalhamento:**
- Geração de NF-e para vendas.
- Geração de relatórios com histórico de notas emitidas.
- Integração com sistemas de emissão de nota fiscal eletrônica (ex.: SEFAZ).
- Possibilidade de cancelamento e correção de notas emitidas.

**Justificativa:** Garantir que o sistema esteja em conformidade com a legislação fiscal vigente e facilitar o processo de emissão de notas.
**Prioridade:** Média


### Avaliação - Especificação de Requisitos

Após a realização do refinamentos do requisitos de nível de usuário para o nível de sistema, em uma nova reunião com o cliente, apresentamos a especificação destes requisitos para que o cliente pudesse realizar a análise e validação.

## Projeto conceitual e especificação do design
![Logo ChocoArte](https://github.com/user-attachments/assets/8d7811ce-1830-4f3f-9342-89459bcb6ac8)

## Wireframe
![Telas do Sistema (2)](https://github.com/user-attachments/assets/c4ef0336-a3d8-407b-9a08-d4b729487aaf)
Figura X - Telas do Sistema
![Página de Login (3)](https://github.com/user-attachments/assets/dbf24920-7813-465d-8a6b-f4cba2f44830)
Figura X - Tela de Login

## Prototipação

## Conclusão


A primeira versão deste projeto foi desenvolvido pelos alunos:

- Lucas Santiago: (Análise e Desenvolvimento de Sistemas).
- Raphael Souza (Análise e Desenvolvimento de Sistemas).
- Ronald Neves: (Análise e Desenvolvimento de Sistemas).
- Samuel Souza (Análise e Desenvolvimento de Sistemas).
- Sérgio Dias: (Análise e Desenvolvimento de Sistemas).

