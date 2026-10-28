# code

def mostrar_menu():
  print("menu")
  print("1- ver mensagem ")
  print("0- sair ")

def mostrar_mensagem():
  print("bem vindo")
mostrar_menu()

opcao= input("escolha: ")

if opcao == "1":
  mostrar_mensagem()
if opcao != "1" and opcao != "0":
   print("opcao invalida")
