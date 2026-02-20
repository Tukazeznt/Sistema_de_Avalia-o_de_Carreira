Este projeto consiste em um sistema web simples desenvolvido em HTML, CSS e JavaScript com o objetivo de automatizar o processo de avaliação anual de desempenho dos
colaboradores
da empresa fictícia TechSoluções.
O sistema foi criado para evitar erros no cálculo manual de reajustes salariais e tornar o processo mais transparente, organizado e justo.

O objetivo principal da atividade é desenvolver um Módulo de Avaliação de Histórico que receba os dados do colaborador, calcule automaticamente o percentual
de reajuste com base no cargo e verifique se ele atende aos critérios de mérito estabelecidos pela empresa. Ao final, o sistema gera um relatório automático informando se 
o reajuste foi aprovado ou bloqueado.

O sistema possui dois grandes blocos visuais: o formulário de avaliação e o painel de histórico. No formulário, o usuário deve preencher o nome do colaborador, selecionar
o cargo, informar o salário atual, a quantidade de faltas e a quantidade de atrasos. Após preencher os dados, basta clicar no botão “Calcular Reajuste” para que o sistema
execute a função de avaliação.

O cálculo do percentual de reajuste varia de acordo com o cargo. O cargo Aprendiz não possui reajuste, o Analista de TI recebe 10%, o Gerente de TI recebe 15% e o Diretor de
TI recebe 20%. Após definir o percentual, o sistema verifica a regra de meritocracia utilizando o operador lógico AND (&&). O colaborador só recebe o reajuste se tiver
exatamente zero faltas e zero atrasos. Caso qualquer um desses valores seja maior que zero, o reajuste é automaticamente bloqueado.

Se o colaborador atender aos critérios, o sistema calcula o valor do aumento com base no percentual definido e soma ao salário atual, exibindo o novo salário formatado
com duas casas decimais. O painel de histórico então apresenta um relatório completo com os dados do colaborador, o percentual aplicado, o valor do aumento, o novo salário
e o status indicando “Reajuste Aprovado”. Caso contrário, o relatório informa que o reajuste foi bloqueado e orienta o colaborador a procurar o RH.

O projeto utiliza conceitos importantes de programação, como estruturas condicionais (if, else if e else), operadores lógicos, manipulação do DOM, conversão de tipos
com parseFloat e parseInt, template strings para formatação do relatório e o método toFixed para exibição correta de valores monetários.

Todo o sistema está organizado em um único arquivo index.html, contendo a estrutura HTML, a estilização CSS interna e o script JavaScript responsável pelas
regras de negócio. Para executar o projeto, basta salvar o arquivo com a extensão .html e abri-lo em qualquer navegador moderno.

Essa atividade reforça conceitos fundamentais de lógica de programação e demonstra como a tecnologia pode ser aplicada para resolver problemas reais dentro de uma
empresa, automatizando processos e reduzindo falhas humanas.
