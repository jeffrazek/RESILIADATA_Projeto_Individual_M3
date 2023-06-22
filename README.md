<h1>RESILIADATA</h1>

> Projeto Individual Módulo 3 - Resília Educação

> Status: Finalizado ✔️

Este projeto foi desenvolvido para mostrar a modelagem física de uma banco de dados para auxiliar na avaliação de quais tecnologias as empresas parceiras estão utilizando e quais os colaboradores das mesmas.

# Como foi feito?

No arquivo jpg contem um print de como ficou as entidades e suas relações. No arquivo txt estão as repostas para as seguintes questões:

+ 1 Quais são as entidades necessárias?
+ 2 Quais são os principais campos e seus respectivos tipos?
+ 3 Como essas entidades estão relacionadas?
+ 4 Simule 2 registros para cada entidade.

Nesta modelagem, o usuário poderia selecionar qual a empresa parceira e após isso mostraria as tecnologias com a opção de selecionar a área (webdev, dados etc) e saber qual o colaborador da empresa está trabalhando nessa tecnologia.

## Exemplo

No arquivo Respostas.txt no final do mesmo contem 2 exemplos de registros dessa modelagem. Abaixo estará uma tabela mais visual desses registros:

Tecnologias
<table>
  <tr></tr>
    <td>ID_TECH</td><td>NOME</td><td>ÁREA</td>
  <tr></tr>
    <tr></tr>
    <td>0001</td><td>Site de Vendas</td><td>Desenvolvimento Web</td>
  <tr></tr>
  <tr></tr>
    <td>0002</td><td>Oracle</td><td>Banco de Dados</td>
  <tr></tr>
</table>

Empresas
<table>
  <tr></tr>
    <td>ID_CNPJ</td><td>Tecnologias_ID_TECH</td><td>NOME</td><td>ENDEREÇO</td><td>CONTATO</td>
  <tr></tr>
    <tr></tr>
    <td>12.345.678/0001-11</td><td>0001</td><td>IO Tech S.A.</td><td>R São Paulo, 10 - Brasília - Arapiraca - AL</td><td>3522-3522</td>
  <tr></tr>
  <tr></tr>
    <td>12.876.543/0002-33</td><td>0002</td><td>SGBD Tech S.A.</td><td>R Alagoas, 44 - Cerejeiras - São Paulo - SP</td><td>3522-1111</td>
  <tr></tr>
</table>

Colaboradores
<table>
  <tr></tr>
    <td>ID_CPF</td><td>Empresas_ID_CNPJ</td><td>NOME</td><td>CARGO</td>
  <tr></tr>
    <tr></tr>
    <td>123.456.789-00</td><td>12.345.678/0001-11</td><td>Aflanildo Pedro de Sá</td><td>Desenvolvedor Web</td>
  <tr></tr>
  <tr></tr>
    <td>112.334.556-77</td><td>12.876.543/0002-33</td><td>Crisóstomo Paulo Assunção</td><td>Analista de Dados</td>
  <tr></tr>
</table>

> ⚠️ Os registros descritos acima são apenas fictícios.
