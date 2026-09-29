cajas = []


def ratioCaja(caja):
    return caja["precio"] / caja["peso"]


def ordenarCajas(lista):
    total = len(lista)
    pos = 0
    while pos < total:
        mejor = pos
        scan = pos
        while scan < total:
            if ratioCaja(lista[scan]) > ratioCaja(lista[mejor]):
                mejor = scan
            paso = 1
            scan = scan + paso
        temp = lista[pos]
        lista[pos] = lista[mejor]
        lista[mejor] = temp
        paso = 1
        pos = pos + paso
    return lista


def mostrarTabla(seleccion, pesoFinal, solesFinal):
    print('========== CAJAS ELEGIDAS ==========')
    for s in seleccion:
        print(f'{s[0]} -> {s[1]:.2f} kg -> S/ {s[2]:.2f}')
    print('------------------------------------')
    print(f'Peso total: {pesoFinal:.2f} kg')
    print(f'Ganancia total: S/ {solesFinal:.2f}')


def llenarMochila(lista, capacidad):
    ordenarCajas(lista)
    pesoActual = 0
    solesActual = 0
    elegidas = []
    for caja in lista:
        if pesoActual < capacidad:
            espacio = capacidad - pesoActual
            if caja["peso"] <= espacio:
                pesoFinal = caja["peso"]
                solesFinal = caja["precio"]
                porcentaje = 100
            else:
                porcentaje = (espacio / caja["peso"]) * 100
                pesoFinal = espacio
                solesFinal = caja["precio"] * (porcentaje / 100)
            pesoActual = pesoActual + pesoFinal
            solesActual = solesActual + solesFinal
            elegidas.append((caja["nombre"], pesoFinal, solesFinal))
            if pesoActual == capacidad:
                break
    mostrarTabla(elegidas, pesoActual, solesActual)


cajas.append({"nombre": "A", "peso": 10, "precio": 4})
cajas.append({"nombre": "B", "peso": 4, "precio": 3})
cajas.append({"nombre": "C", "peso": 7, "precio": 3})
cajas.append({"nombre": "D", "peso": 5, "precio": 2})
cajas.append({"nombre": "E", "peso": 3, "precio": 1})
cajas.append({"nombre": "F", "peso": 3, "precio": 2})
cajas.append({"nombre": "G", "peso": 2, "precio": 1.8})
cajas.append({"nombre": "H", "peso": 3, "precio": 3})

capacidad = float(input('Ingrese peso maximo de la mochila: '))

llenarMochila(cajas, capacidad)