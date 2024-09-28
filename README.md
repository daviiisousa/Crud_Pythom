
# Simulação de banco de dados com listas de dicionários
veiculos = []
clientes = []
vendedores = []
vendas = []

# Funções CRUD para veículos
def cadastrar_veiculo():
    id_veiculo = len(veiculos) + 1
    marca = input("Digite a marca do veículo: ")
    modelo = input("Digite o modelo do veículo: ")
    ano = input("Digite o ano do veículo: ")
    cor = input("Digite a cor do veículo: ")
    preco = float(input("Digite o preço do veículo: "))
    status = "disponível"
