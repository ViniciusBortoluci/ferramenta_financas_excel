### Desafio Ferramenta de Finanças

#### Entendendo o desafio:

Nesse desafio criei de uma planilha com cara de aplicativo, usada com base as aulas do desafio do Bootcamp "Formação Análise de Dados com Excel e IA", com o objetivo que responder às cinco perguntas de negócio:

- Quanto investir por mês;
- Por quantos anos;
- Qual a taxa de rendimento mensal;
- Quanto de patrimônio vai acumular;
- Quanto vai receber de dividendos por mês.

#### Oque foi feito:

 - Criação de um bunner, e formatações para esconder as linhas de grade e pintar de cinza as célular que não se pode mexer 
 - Utilização da função VF(), para achar o patrimônio acumulado e assim os dividendos mensais;
 - Foi criado uma tabela com os rendimentos para 2, 5, 10, 20, 30 anos e seus dividendos;
 - Criado salário, rendimento da certeira e sugestão de aporte de 30% do salário;
 - Criado um lista de perfis com validação de dados. Utilizando uma aba de apoio com perfil, tipo de fundoi, percentual e puxado para a planilha principál utilizando o PROCV e uma chave composta;

 #### Ideias para Evoluir:

- Um gráfico de pizza com a divisão do aporte, que mude junto com o perfil;
- Uma segunda simulação que use a sugestão de 30% do salário no lugar do aporte informado;
- Novas projeções, sempre com tabela de apoio e intervalos nomeados;
- Esconder a barra de fórmulas, os títulos e as guias na versão final;

#### O Que Entregar:

1. As perguntas que a ferramenta responde, e onde aparece cada resposta;

Quanto devo investir por mês?
Na ferramenta atual está com um salário de 8000 e com 30% de percentual de investimento, e aparece na célula D18.

Quanto terei no prazo escolhido?
Com a função VF() e ferramenta pega o aporte, anos em mesese e taxa mensal onde passa o valor recorrente. Célula D24

Quanto isso pode gerar de dividendos mensais?
Temos dividendos com Patrimônio e rendimento da carteira, que é uma estimativa e não uma garantia, célula D25.

Quanto terei em 2, 5, 10, 20 e 30 anos?
Criada uma tabela onde temos os rendimentos para 5 quantidade de anos, onde temos o valor pelos anos e o dividendo recebido, C28:C32

Como distribuir um valor entre tipos de FII?
São distribuídos pelo valor e perfil, C39:C44

2. Como o VF e o PROCV entram nos cálculos;
o VF() entra em patrimônio acumulado e cenários fixos, células D24 e C28:C32. já o PROCV busca os valores da planilha de apoio para a principal, trazendo uma chave combinada com perfil e tipo de investimento, C39:C44

3. Os intervalos nomeados que você criou;
 Aporte - D21
 Patrimonio - D24
 qtd_anos - D22
 Rendimento_Carteira - D17
 Sugestão_investimento - D18
 taxa_mensal - D23

4. Os percentuais de cada perfil;
![alt text](image-2.png)

5. O que você mudou em relação à ferramenta do Expert.
- Sugestão de investimento automatizada, onde salário tem automaticamente 20% ou 30% do salario passado, onde o percentual é escolhido em uma tabalinha com uma validação de dados. Cálula D18

- Correção do perfil Modertado que estava com uma soma de 177% e agora passei para 100%;
- Valores por FII automatizados;
- Validações de entrada em Rendimento Carteira, para escolher entre 0,6%, 0,8% ou 1% na taxa, onde mostra o tipo de investidor e a porcentagem, célula D17;
- Validação de dados nos anos, passados valores 1, 5, 10, 15, 20, 25 e 30, célula D22;
- Refeito o gráfico de pizza trazendo mais informações como tipo e percentual, e criado um gráfico de barras com os valores dos dividendos;
- Criei uma outra tabela de Perfil de investidor passando aporte de 30% do salário tendo o cálculo automático do tipos de FII, com gráficos para melhor entendimento;
- Adicionei a função ARRED() na formula VF() para facilitar passar o tempo de ano para meses;
- Criei um gráfico de linhas que mostra o Rendimento ao passar dos anos;
- Criei um gráfico de cascata mostrando a porcentagem de ganho em relação aos anos;





 
