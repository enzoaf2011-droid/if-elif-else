# Basic

# if-elif-else
A little bit of this. 

 # Versão Refatorada e mais Lógica

idade = 11 # Mude para testar

print("Analisando a faixa etária de uma pessoa com", idade, "anos...")

if idade >= 18:
    print("Resultado: Pessoa maior de idade.")
    print("Direitos: Pode dirigir e o voto é obrigatório.")

elif idade >= 16: # Captura 16 e 17
    print("Resultado: Emancipado para fins de votação.")
    print("Direitos: Voto opcional, mas ainda não pode dirigir.")

elif idade == 15: # Específico para 15
    print("Resultado: Adolescente de 15 anos.")
    print("Direitos: Menor; não pode votar nem dirigir; é necessário tomar cuidado!")

elif idade == 14: # Específico para 14
    print("Resultado: Adolescente de 14 anos.")
    print("Direitos: Menor; não pode votar nem dirigir; necessita de supervisão.")
    
# Podemos juntar os outros casos em um 'else' mais geral
else:
    # Este bloco agora captura 13, 12, 11... qualquer coisa abaixo de 14.
    print("Resultado: Pessoa menor de idade/pré-adolescente.")
    print("Direitos: Menor; não pode votar nem dirigir.")

print("--- Análise concluída ---")
# ...existing code...





