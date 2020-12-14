# USUARIO-E-SENHA
Lê um nome de usuário e a sua senha e não aceite a senha igual ao nome do usuário, mostrando uma mensagem de erro e voltando a pedir as informações.

usuario = str(input("Digite o usuário: "))
senha = str(input("Digite a senha: "))
while usuario == senha:
  print("A senha não pode ser igual ao usuário")
  usuario = str(input("Digite o usuário: "))
  senha = str(input("Digite a senha: "))
