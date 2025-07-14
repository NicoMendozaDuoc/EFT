#productos = {modelo: [marca, pantalla, RAM, disco, GB de DD, procesador, video]


productos = {'8475HD': ['HP', 15.6, '8GB', 'DD', '1T', 'Intel Core i5', 'Nvidia GTX1050'],
 '2175HD': ['lenovo', 14, '4GB', 'SSD', '512GB', 'Intel Core i5', 'Nvidia GTX1050'],
 'JjfFHD': ['Asus', 14, '16GB', 'SSD', '256GB', 'Intel Core i7', 'Nvidia RTX2080Ti'],
 'fgdxFHD': ['HP', 15.6, '8GB', 'DD', '1T', 'Intel Core i3', 'integrada'],
 'GF75HD': ['Asus', 15.6, '8GB', 'DD', '1T', 'Intel Core i7', 'Nvidia GTX1050'],
 '123FHD': ['lenovo', 14, '6GB', 'DD', '1T', 'AMD Ryzen 5', 'integrada'],
 '342FHD': ['lenovo', 15.6, '8GB', 'DD', '1T', 'AMD Ryzen 7', 'Nvidia GTX1050'],
 'UWU131HD': ['Dell', 15.6, '8GB', 'DD', '1T', 'AMD Ryzen 3', 'Nvidia GTX1050'],
 }

#stock = {modelo: [precio, stock], ...]

stock = {'8475HD': [387990,10], '2175HD': [327990,4], 'JjfFHD': [424990,1],
 'fgdxFHD': [664990,21], '123FHD': [290890,32], '342FHD': [444990,7],
 'GF75HD': [749990,2], 'UWU131HD': [349990,1], 'FS1230HD': [249990,0],
 }

marca=""
marca_consultar="" 
cantidad_marca=0
modelo=""
minimo=0
maximo=0
marca_precio={}
modelo_actualizar=""
precio_nuevo=0


def menu_principal():
    print('''           *** MENU PRINCIPAL ***
            1. Stock marca.
            2. Búsqueda por precio.
            3. Actualizar precio.
            4. Salir.''')

# def stock_marca(marca):
#     marca_consultar=input("Ingrese marca a consultar: ").strip().upper()
#     print(marca_consultar)
#     if marca_consultar in productos:{}
#         modelo = productos = {}
#         for i in stock:
#             if modelo in stock :
#                 cantidad_marca=cantidad_marca+1
#     else:
#         print("El stock es: 0.")            
    

# def busqueda_precio():
#     try:     
#         minimo=input(f"Ingrese precio mínimo: ")
#         maximo=input(f"Ingrese precio máximo: ")  
#         for i in len(stock):
#             if stock[0]>minimo and stock[0]<maximo:
#                 modelo = stock={}
#                 if modelo in productos:{}
#                     marca_precio{}= productos[0], stock[0]

#         print(f"Los notebooks entre los precios consultas son: {marca_precio}")
#     except Exception as e:
#         print(fe)

# def actualizar_precio():
#     while True: 
#         print(f"Productos disponibles: \n{productos}")
#         modelo_actualizar=input("Ingrese modelo a actualizar: ").strip().upper()
#         precio_nuevo=int(input("Ingrese el nuevo precio: "))
#         if modelo_actualizar in stock:
#             precio_nuevo = stock{modelo_actualizar[0]}
#             print("Precio actualizado!!")
#         sn=input("Desea actualizar otro precio? (s/n): ")
#         if sn=="s":
#             print(f"Productos disponibles: \n{productos}")
#         modelo_actualizar=input("Ingrese modelo a actualizar: ").strip().upper()
#         precio_nuevo=int(input("Ingrese el nuevo precio: "))
#         if modelo_actualizar in stock:
#             precio_nuevo = stock{modelo_actualizar[0]}
#             print("Precio actualizado!!")
#         else:
#             break


while True:

    menu_principal()
    op=int(input("Ingrese opción: "))
    match op:
        case 1:
            stock_marca(marca)
        case 2:
            busqueda_precio()
        case 3:
            actualizar_precio()
        case 4:
            print("Programa finalizado.")
            break
