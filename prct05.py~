#!/usr/bin/python

PI=3.1415926535897931159979634685441852
n= int(raw_input('Introduzca el numero de intervalos(n>0): '))
print 'El numero de intervalos es: %d' % (n)
print ' '
suma=0.0
for i in range(1,n+1):
  a= (i-1.0)/float(n)
  b= i/float(n)
  x_i= (i-0.5)/float(n) 
  f= 4.0/(1+((x_i)**2))
  print 'Subintervalo: [%f , %f] x_%d : %f f(x_%d) es: %f' % (a, b, i, x_i, i, f)
  print ' '
  suma=suma+f
pi=(1/float(n))*suma
print 'El valor aproximado del numero pi es: %f' % (pi)
print 'El valor de PI con 35 decimales es: %1.35g' % (PI)
print ' '

