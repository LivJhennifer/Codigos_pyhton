from random import randint 
s = 0
while True:
  n = int(input('digite um número:'))
  computador = randint(0,11)
  m = str(input('ímpar ou par?[I/P]:')).strip().upper()[0]
  while m not in 'pPiI':
  	m = str(input('ímpar ou par[I/P]:')).strip().upper()[0]
  a = computador + n 
  print(f'você jogou {n} e o computador jogou {computador}. o total foi {a}')
  if a % 2 == 0 and m in 'Pp':
    s += 1
    print(' você ganhou')
  else: 
    if a % 2 != 0 and m in 'Ii':
      s += 1 
      print(' você ganhou ')
    else:
      break 
print(f' você ganhou {s} vezes')
  
