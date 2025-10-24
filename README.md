# if-elif-else
A little bit of this.
# ...existing code...
idade = 14 


print("Analisando a faixa etária de uma pessoa com", idade, "anos...")

if idade >= 18:
    # Caminho 1: Maior de idade
    print("Resultado: Pessoa maior de idade.")
    print("Direitos: Pode dirigir e o voto é obrigatório.")

elif idade >= 16:
    # Caminho 2: Só executa se o 'if' acima for False
    print("Resultado: Emancipado para fins de votação.")
    print("Direitos: Voto opcional, mas ainda não pode dirigir.")

elif idade >= 13:
    # Novo caminho: adolescentes de 13 a 15 anos
    print("Resultado: Adolescente.")
    print("Direitos: Menor; não pode votar nem dirigir; necessita de supervisão.")

else:
    # Caminho 3: Só executa se tanto o 'if' quanto o 'elif' forem False
    print("Resultado: Pessoa menor de idade.")
    print("Direitos: Não pode votar nem dirigir.")

print("--- Análise concluída ---")
# ...existing code..
