# Pilas-programacion-
1- dar vuelta pila :
 def -- init -- (self) :
      self.items == []

 def esta vacia (self) :
     return self.items == []

def incluir (self item) :
    self.items.append (item)

def inspeccionar (self)no borra
    return ( self.items [lenght (self.items) -1]

def extraer (self):borra
    return(self.items.pop () )

def tamaño (self)
    return ( lenght (self.items))

2 a)def dar vuelta (self) :
    q = pila()
    while not p.estavacia()
      q incluir(p.extraer())
self.items=q.items 

b) def imprimir (self):
  print(pila.pop())
  print(pila)


c) def extraer (self):
 while not.p self
      self p.extraer 
3) def dar vuelta (self):
     if "Python Diario Mi"
     return true 
else return "my diario paython"
     return false 
    
4) def inspeccionar (self):
       if misma cantidad 0 y 1 
        return true 
       else no tiene la misma cantidad 
        return false 

5) ej (1+2) (5+3))
respuesta = true 
  p = true 
p= pila ()

for in s :
    if x == c 
    abre.incluir (x)
if x== j
   if p.vacia () :
      resp = false 
if! p.vacia () :
    p.extraer ()
if tamaño p = 0
   resp = falso 

return respuesta 
6-
rom pythoned.basicas.pila import Pila

def verificarSimbolos(cadenaSimbolos):
    p = Pila()
    balanceados = True
    indice = 0
    while indice < len(cadenaSimbolos) and balanceados:
        simbolo = cadenaSimbolos[indice]
        if simbolo in "([{":
            p.incluir(simbolo)
        else:
            if p.estaVacia():
                balanceados = False
            else:
                tope = p.extraer()
                if not parejas(tope,simbolo):
                       balanceados = False
        indice = indice + 1
    if balanceados and p.estaVacia():
        return True
    else:
        return False

def parejas(simboloApertura, simboloCierre):
    aperturas = "([{"
    cierres = ")]}"
    return aperturas.index(simboloApertura) == cierres.index(simboloCierre)


print(verificarSimbolos('{{([][])}()}'))
print(verificarSimbolos('[{()]'))

7- 
Usando pilas defina una función que diga si una palabra es capicua. Entrada: Estandarte Salida: True 
class Cadenas:

    def __init__ (self, cad1):

        self.cad1=cad1

        #self.cad2=cad2

    def pal(self):

        cad1,c,i,nom,cad,x = '',0,0,'','',''

        i = len(cad1)

        nom = cad1.lower()

        while i != c:

            for x in nom:

                cad = x + cad

                c=c+1

            if nom==cad:

                print (cad1, " Es Palindromo")

            else:

                print (cad1, " No es Palindromo")

        return cad1

 

cad1 = str(input('Dame una palabra: '))

op1=Cadenas(cad1)

print(op1.pal)

8)
def __init__(self):
    self.items = [] 


def estaVacia(self): 
    return self.items == []
 

def incluir(self, item):
    self.items.insert(0,item)


def extraer(self): 
    return self.items.pop(0)
    

def inspeccionar(self):
    return self.items[0] 


def tamano(self):
     return len(self.items) 

