<h1 align="center">
📄<br> Meus Algoritmos Iniciais... 
</h1>

<h1 align="center">
 <img align="center" alt="Walkemyr-pic" height="640" style="border-radius:640px;" 
 src="https://cdn.discordapp.com/attachments/712667373060227102/1014949367515467826/Sem_Titulo-1.png">
 
 ##
 
 </div>
 
 <h1 align="center">
📄<br> Primeira Atividade com Pascalzin... 
</h1>

 ## ☑️ Primeiro Algoritmo PascalZim
 
 program Pzao01Soma;
var n1, n2, n3, n4, soma: integer;
begin
  {Mostra o resultado da soma}
  write ('Digite o primeiro numero > ');
  
  {Recebe o numero}
  read (n1);
  
  {Mostra o resultado da soma}
  write ('Digite o segundo numero > ');
  
  {Recebe O numero}
  read (n2);
  
  {Mostra o resultado da soma}
  write ('Digite o terceiro numero > ');
  
  {Recebe o numero}
  read (n3);
  
  {Mostra o resultado da soma}
  write ('Digite o quarto numero > ');
  
  {Recebe o numero}
  read (n4);
  
  {Mostra o resultado da soma}
  soma:= n1+n2+n3+n4;
  write ('Resultado: ',soma);
  
end.

 ## ☑️ Segundo Algoritmo PascalZim
 
 program Pzao02Media; var n1, n2, n3, media: Real;
begin

  writeln ('Digite a primeira nota :');
  read (n1);
  
  writeln ('Digite a segunda nota :');
  read (n2);
  
  writeln ('Digite a terceira nota :');
  read (n3);
  
  media:= (n1+n2+n3)/3;
  writeln ('A media das notas Ã© :',media);
  
end.

## ☑️ Terceiro Algoritmo PascalZim

program Pzao03Ponderada; var n1, n2, n3, p1, p2, p3, mediapon: Real;
begin

  writeln ('Digite a primeira nota :');
  read (n1);
  
  writeln ('Digite a segunda nota :');
  read (n2);
  
  writeln ('Digite a terceita nota :');
  read (n3);
  
  writeln ('Digite o peso da primeira nota :');
  read (p1);
  
  writeln ('Digite o peso da segunda nota :');
  read (p2);
  
  writeln ('Digite o peso da terceira nota :');
  read (p3);
  
  mediapon:= ((n1*p1)+(n2*p2)+(n3*p3))/(p1+p2+p3);
  writeln ('A media ponderada das 3 notas Ã© :',mediapon);
  
end.

 ## ☑️ Quarto Algoritmo PascalZim
 
 program Pzao04Salario; var sal, novosal: Real;
begin

  writeln ('Digite o salario :');
  read (sal);
  
  novosal:= sal*1.25;
  writeln ('O salario com aumento de 25% fica :', novosal);
  
end.

 ## ☑️ Quinto Algoritmo PascalZim

program Pzao05Salario; var sal, aumento, novosal: Real;
begin

  //   Limpar Tela
  clrscr;
  //  Recebe o valor do salario
  
  writeln ('Digite o valor do salario :');
  
  // ler salario
  read (sal);
  
  //  recebe o valor em porcentagem
  writeln ('Digite o valor do aumento em porcentagem :');
  
  // ler aumento
  read (aumento);
  
  //  calcula aumento
  aumento:= sal*(aumento/100);
  
  // soma aumento com o salario
  novosal:= aumento+sal;
  
  //  mostra o valor do aumento em porcentagem
  writeln ('O valor do aumento em porcentagem é :',aumento);
  
  // mostra o novo salario com aumento
  writeln ('O valor do novo salario é ',novosal :5:2,' reais');
  
end.

## ☑️ Sexto Algoritmo PascalZim

program Pzao06Salario; var sal, grat, imp, desc, novosal: Real;
begin

  //   Limpar Tela
  clrscr;
  
  // recebe o salario base do funcionario 
  writeln ('Digite o salario base do Funcionario :');
  
  // ler salario
  read (sal);
  
  // calcula gratificação
  grat:= sal*0.05;
  
  // calcula imposto
  imp:= sal*0.07;
  
  // calcula desconto
  desc:= sal-imp;
  
  // calcula desconto e gratificação
  novosal:= desc+grat;
  
  // mostra o novo salario com todos os calculos
  writeln ('O novo salario do funcionario a receber é de :',novosal :5:2, ' reais');
  
end.

## ☑️ Setimo Algoritmo PascalZim

program Pzao07Salario; var sal, imp, novosal: Real;
begin

  //   Limpar Tela
  clrscr;
  
  // recebe o salario do funcionario
  writeln ('Digite o salario base do funcionario :');
  
  // ler salario
  read (sal);
  
  // calcula salario com aumento
  imp:= sal*0.10;
  
  // calcula salario com imposto e gratificação
  novosal:= (sal-imp)+50;
  
  // mostra novo salario com todos os calculos
  writeln ('O novo salario que o funcionario tem a receber é de ',novosal :5:2, ' reais');
  
end.

## ☑️ Oitavo Algoritmo PascalZim

program Pzao08Deposito; var deposito, taxa, rend, total: Real;
begin

  //   Limpar Tela
  clrscr;
  
  // recebe o valor do deposito
  writeln ('Digite o valor do deposito :');
  
  // ler deposito
  read (deposito);
  
  // recebe o valor da taxa de juros
  writeln ('Digite o valor da taxa de juros :');
  
  // ler taxa de juros
  read (taxa);
  
// calcula renda, deposito e taxa
rend:= deposito*(taxa/100);

// calcula deposito e renda
total:= deposito+rend;

// mostra o valor do rendimento
writeln ('O valor do rendimento é de ',rend :5:2, ' reais');

// mostra o valor total apos rendimento
writeln ('O valor total apos o rendimento é de ',total :5:2, 'reais');

end.

</div>

##

 <h1 align="center">
📄<br> Segunda Atividade com Pascalzin... 
</h1>

