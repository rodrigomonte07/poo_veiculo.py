class Veiculo():

    def movimentar(self):
        print("Veículo está em movimento.") 
    
class Carro(Veiculo):

    def movimentar(self):
        print("Carro está dirigindo.") 
    
class Moto(Veiculo):

    def movimentar(self):
        print("Moto está acelerando")
    
veiculo_1 = Veiculo()
carro_1 = Carro()
moto_1 = Moto()

veiculo_1.movimentar()
carro_1.movimentar()
moto_1.movimentar()
