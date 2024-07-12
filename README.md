# Diccionario de palabras y sus significados
meme_dict = {
    "LOL": "Una respuesta a algo gracioso",
    "CRINGE": "Algo excepcionalmente raro o embarazoso",
    "ROFL": "Una respuesta a una broma",
    "SHEESH": "Ligera desaprobación",
    "CREEPY": "Aterrador, siniestro",
    "AGGRO": "Ponerse agresivo/enojado",
}

# Saludo e instrucciones
print("¡Bienvenido a la aplicación de diccionario de memes!")
print("Puedes escribir hasta 5 palabras que no entiendas (¡con mayúsculas!)")

# Bucle para preguntar 5 palabras
for _ in range(5):
    word = input("Escribe una palabra que no entiendas: ")
    if word in meme_dict:
        print(word + ": " + meme_dict[word])
    else:
        print("La palabra '" + word + "' no se encuentra en el diccionario.")

print("¡Gracias por usar la aplicación de diccionario de memes!")
