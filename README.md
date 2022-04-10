# Do-Zero-ao-um
Visualg
Calcular a Média de notas
--------------------------------------------------------------------------//////---------------------------------------------------------------
Algoritmo "semnome"
// Disciplina   : [Linguagem e Lógica de Programação]
// Autor(a)    : Nome do(a) aluno(a)
// Data atual  : 03/04/2022
var
NOTA1, NOTA2, NOTA3, NOTA4, MEDIA : REAL


inicio
// Seção de Comandos
 ESCREVA("DIGITE A PRIMEIRA NOTA: ")
 LEIA(NOTA1)
 ESCREVA("DIGITE A SEGUNDA NOTA: ")
 LEIA(NOTA2)
 ESCREVA("DIGITE A TECEIRA NOTA: ")
 LEIA(NOTA3)
 ESCREVA("DIGITE A QUARTA NOTA: ")
 LEIA(NOTA4)
 MEDIA := (NOTA1 + NOTA2 + NOTA3 + NOTA4) / 4 ;
                      SE MEDIA <= 4  ENTAO
 ESCREVA("A MEDIA DO ALUNO FOI: ", MEDIA)
    ESCREVAL (" - ALUNO REPROVADO ")
 FIMSE
 SE MEDIA <=  6.9 ENTAO
    ESCREVA("A MEDIA DO ALUNO FOI: ", MEDIA)
    ESCREVAL (" - ALUNO DE RECUPERAÇÃO ")
 FIMSE
 SE MEDIA >= 7 ENTAO
    ESCREVA("A MEDIA DO ALUNO FOI: ", MEDIA)
    ESCREVAL (" - ALUNO APROVADO ")
 FIMSE

fimalgoritmo
