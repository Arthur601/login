nome_cadastro = input("digite seu nome de usuário: ")
senha_cadastro = input("digite sua senha: ")

print("Cadastrado com sucesso!!")
nome_digitado = input("digite seu usuário: ")
senha_digitada = input("digite sua senha: ")
if nome_cadastro == nome_digitado and senha_cadastro == senha_digitada:
    print("Logado com sucesso!!")
else:
      print("Usuário e senha estão incorretos.")
