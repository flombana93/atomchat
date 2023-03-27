# atomchat

#Este codigo fue echo en python 

def say_hello():
  print('Hola')
    
say_hello()

def say_welcome():
  name = input('¡Bienvenido! Gracias por comunicarse con Tokio Inc ¿Con quién tengo el gusto?')
  while name == '':
    print('Nombre:')
    name = input('Nombre:')
  print(name,'¿Cómo podemos ayudarle el día de hoy?')
    
  option = input("\n 1.Comprar un producto \n 2.Información de productos \n 3.Atención al cliente \n ")
  if option == '1':
    zone = input("Seleccione la Zona \n 1.Managua \n 2.Buenos Aires \n 3.Santiago \n 4.Medellin \n 5.Perú ")
    if zone == '1':
      print('Excelente', name ,'Nos puede brindar más detalles del producto de su interés, mientras le transfiero con un asesor de la Zona Managua para asistirlo en su compra')
    elif zone == '2':
      print('Excelente', name ,'Nos puede brindar más detalles del producto de su interés, mientras le transfiero con un asesor de la Zona Buenos Aires para asistirlo en su compra')
    elif zone == '3':
      print('Excelente', name ,'Nos puede brindar más detalles del producto de su interés, mientras le transfiero con un asesor de la Zona Santiago para asistirlo en su compra')
    elif zone == '4':
      print('Excelente', name ,'Nos puede brindar más detalles del producto de su interés, mientras le transfiero con un asesor de la Zona Medellin para asistirlo en su compra')
    elif zone == '5':
      print('Excelente', name ,'Nos puede brindar más detalles del producto de su interés, mientras le transfiero con un asesor de la Zona Perú para asistirlo en su compra')
    else:
        zone = input("Seleccione la Zona \n 1.Managua \n 2.Buenos Aires \n 3.Santiago \n 4.Medellin \n 5.Perú ")
  elif option == '2':
    print("En breve estará recibiendo nuestro catálogo donde encontrará todos los productos que necesita https://bit.ly/staria11-details ")
  elif option == '3':
    option3 = input("seleccione la opción que desea consultar: \n 1. Horarios y sucursales \n 2. Medios de Pago \n 3. Hablar con un asesor ")
    if option3 == '1':
      print("Estimado cliente, atendemos de Lunes a Domingo de 7am a 7pm")
    elif option3 == '2':
      print("Aceptamos tarjetas de crédito, efectivo y transferencias")
    elif option3 == '3':
      print("Le estamos comunicando con uno de nuestros asesores")
say_welcome()
