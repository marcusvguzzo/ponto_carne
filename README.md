temperatura = int(input('Qual a temperatura da carne? '))


if temperatura <= 48:
    print(f'Temperatura está em {temperatura}°C. Nesse ponto, está selada')

elif temperatura <= 54:
    print(f'Temperatura está em {temperatura}°C. A carne está ao ponto para mal')

elif temperatura <= 60:
    print(f'Temperatura está em {temperatura}°C. A carne está ao ponto')

elif temperatura <= 65:
    print(f'Temperatura está em {temperatura}°C. A carne está ao ponto para bem')

else:
    print(f'Temperatura está em {temperatura}°C. A carne está bem passada')
