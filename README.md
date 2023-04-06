# acoes
Código utilizando a função Classe para acompanhar ações
class ações:
    nome: ''
    valor=0
    tipo= ''
    ramo=''
    def __init__(self,n,v,t,r):
          self.nome=n
          self.valor=v
          self.tipo=t
          self.ramo=r
    def mostrar(self):
      print('Nome :   ' + str(self.nome))
      print('Valor:   R$ ' + str(self.valor))
      print('Tipo :  ' + str(self.tipo))
      print('Ramo :  ' + str(self.ramo)) 
      print('-----------------------------')
 a1=ações('ZAMP3', 3.93, 'on', 'Bens Industrias')
 a2=ações('ASAI3', 13.97, 'on', 'Varejo')
 a2=ações('ASAI3', 13.97, 'on', 'Varejo')
a1.mostrar()
a2.mostrar()
a3.mostrar()
