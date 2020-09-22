# divisionNaturalAtmega328
; division.inc
; Funciones para dividir numeros naturales de 8 y 16 bits 
; utilizando algoritmo utilizado por software ATMEL STUDIo para este tipo de división
; AUTOR: UADER-FCYT 
; Versión 1.0 
; Fecha 21-09-2020
 
; División por 16 bits
; DIVIDENDO -> R24:R25
; DIVISOR   -> R23:R22
; RESTO		-> R27:R26
; COCIENTE	-> A lo largo del algoritmo se modifica el DIVIDENDO y el COCIENTE queda en R24:R25
; R21 también es modificado en el desarrollo de la operación
			
; División por 8 bits
; DIVIDENDO -> R24
; DIVISOR   -> R22
; RESTO		-> R25
; COCIENTE	-> A lo largo del algoritmo se modifica el DIVIDENDO y el COCIENTE queda en R24
; R23 también es modificado en el desarrollo de la operación
