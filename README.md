class Barbearia:
    def __init__(self, nome):
        self.nome = nome
        self.servicos = []

    def adicionar_servico(self, servico):
        self.servicos.append(servico)
        print(f"Serviço de {servico} adicionado com sucesso!")

    def realizar_corte_cabelo(self):
        print("Realizando corte de cabelo...")
        # Lógica para realizar o corte de cabelo

    def fazer_barba(self):
        print("Realizando corte de barba...")
        # Lógica para fazer a barba

    def exibir_servicos(self):
        print(f"Serviços oferecidos por {self.nome}:")
        for servico in self.servicos:
            print(f"- {servico}")

# Criando uma instância da Barbearia
alura_barbearia = Barbearia("Alura Barbearia")

# Adicionando serviços
alura_barbearia.adicionar_servico("Corte de Cabelo")
alura_barbearia.adicionar_servico("Barba")

# Exibindo os serviços
alura_barbearia.exibir_servicos()

# Realizando um corte de cabelo
alura_barbearia.realizar_corte_cabelo()

# Fazendo uma barba
alura_barbearia.fazer_barba()

