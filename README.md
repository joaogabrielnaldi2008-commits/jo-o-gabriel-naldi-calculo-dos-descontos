# jo-o-gabriel-naldi-calculo-dos-descontos
# Sistema de desconto progressivo

valor_compra = float(input("Digite o valor total da compra: R$ "))

if valor_compra < 200:
    percentual = 0.05
elif valor_compra < 300:
    percentual = 0.10
else:
    percentual = 0.15

desconto = valor_compra * percentual
valor_final = valor_compra - desconto

print("\n--- Resumo da compra ---")
print(f"Valor da compra: R$ {valor_compra:.2f}")
print(f"Desconto aplicado: R$ {desconto:.2f}")
print(f"Total a pagar: R$ {valor_final:.2f}")
