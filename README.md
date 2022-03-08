# Informe trabajo extra - Creación y simulación de un sumador no inversor

1. OBJETIVOS 

- Objetivo general:

Construir  y simular un sumador no inversor

- Objetivos específicos:

  - Explicar el funcionamiento de un amplificador operacional sumador no inversor 
  
  - Fabricar un circuito que sume dos voltajes de entrada 


2. MARCO TEÓRICO

![Untitled](https://user-images.githubusercontent.com/93950169/156969893-3f6387de-ce41-4ced-a394-4742b56dcf29.jpg)

3. MATERIALES

- Dos pilas doble A 1.6 V
- Dos baterias de 9V
- Dos resistencias de 2000 ohmios
- Dos resistencias de 1000 ohmios
- Un amplificador operacional 741
- Un multimetro

4. PROCEDIMIENTO

  Se realiza el calclulo de previo para obtener el voltaje de salida

  Para obtener el voltaje de salida se obtiene Vx1 y Vx2.

  Vx1 se obtiene por superposición.

  Cuando V2=0 mediante la aplicación del divisor de voltaje:

  ![lagrida_latex_editor (2)](https://user-images.githubusercontent.com/93950169/156972346-2eaad2b2-660b-4889-81b7-eee86657ba93.png)

  Cuando V1=0 mediante la aplicación del divisor de voltaje:

  ![lagrida_latex_editor (1)](https://user-images.githubusercontent.com/93950169/156972259-575d1a30-e166-4e50-aa27-cd6ab50ed40c.png)

  Se suman los Vx1:

  ![lagrida_latex_editor (3)](https://user-images.githubusercontent.com/93950169/156972614-0b081888-414a-4fa5-9d8c-7df1a69f58db.png)

  Mediante el divisor de voltaje:

  ![lagrida_latex_editor (4)](https://user-images.githubusercontent.com/93950169/156972830-6e3aca42-76d4-48c8-9a6e-90a26d33c67a.png)

  Se sabe que Vx1 = Vx2:

  ![lagrida_latex_editor (5)](https://user-images.githubusercontent.com/93950169/156973194-1a171017-af88-4ace-9788-ae69ba3db1ff.png)

  ![lagrida_latex_editor (6)](https://user-images.githubusercontent.com/93950169/156973495-00d15a39-a582-425c-b8a8-5144cd1599e6.png)

  Realizar un circuito que obtenga: ![lagrida_latex_editor (7)](https://user-images.githubusercontent.com/93950169/156973618-d1b19d04-5c8a-4a3f-9f36-9f997b351250.png)

  ![lagrida_latex_editor (8)](https://user-images.githubusercontent.com/93950169/156974095-6409d80b-8f74-4edb-8b09-6908a76e4179.png)

  ![lagrida_latex_editor (9)](https://user-images.githubusercontent.com/93950169/156974209-6e99b331-caab-4f72-b4f1-ca3a9dbc0977.png)

  ![lagrida_latex_editor (13)](https://user-images.githubusercontent.com/93950169/156975654-c3f07e5c-effe-460c-a551-8ebf174acd6d.png)

  Se propone que: ![lagrida_latex_editor (11)](https://user-images.githubusercontent.com/93950169/156974778-762b6949-1923-4639-9997-0f9d7e9fbd41.png) y ![lagrida_latex_editor (14)](https://user-images.githubusercontent.com/93950169/156975752-60046830-8c36-46b7-9858-0816aa9df0f5.png)

  Ganancia 1:

  ![lagrida_latex_editor (15)](https://user-images.githubusercontent.com/93950169/156975984-6fa50e21-d2ea-4288-a416-18a655aba659.png)

  ![lagrida_latex_editor (16)](https://user-images.githubusercontent.com/93950169/156976091-0529cab5-eeb6-4e14-adcf-6e725977c94e.png)

  Ganancia 2:

  ![lagrida_latex_editor (17)](https://user-images.githubusercontent.com/93950169/156976207-8eb59d91-001a-4dc4-b10b-3758ab410792.png)

  ![lagrida_latex_editor (18)](https://user-images.githubusercontent.com/93950169/156976271-b665f79d-c3b0-43c2-9cff-2c99ed1c23ed.png)

  Se igualan las ganancias:

  ![lagrida_latex_editor (19)](https://user-images.githubusercontent.com/93950169/156976433-161fa39f-23be-4434-a31c-fe954ca37a49.png)

  Se despeja R2:

  ![lagrida_latex_editor (20)](https://user-images.githubusercontent.com/93950169/156976655-116b256b-7531-46a9-ae5a-32715b616676.png)

  Si se dice que:

  ![lagrida_latex_editor (25)](https://user-images.githubusercontent.com/93950169/156976968-5fc8d735-a0b9-48eb-86be-ebc9a4183c7e.png)

  Entonces ![lagrida_latex_editor (26)](https://user-images.githubusercontent.com/93950169/156977036-d6ecdafa-20a4-4760-ae95-e7ce94d7390a.png)

  Por lo tanto: 

  ![lagrida_latex_editor (21)](https://user-images.githubusercontent.com/93950169/156976745-3afd0ee5-fbfe-4711-8c23-1a6879833d01.png)

  ![lagrida_latex_editor (22)](https://user-images.githubusercontent.com/93950169/156976779-3f88b910-4c07-4fb9-a5e0-f4c1c5232f27.png)

  ![lagrida_latex_editor (23)](https://user-images.githubusercontent.com/93950169/156976844-577def94-9b60-4450-85a1-0c7f3e4c213d.png)

  ![lagrida_latex_editor (24)](https://user-images.githubusercontent.com/93950169/156976881-9cb399d9-73cb-4006-a951-4f4f9f44dfd0.png)

  Con los datos obtenidos se realiza la simulación en el programa multisim, se utilizó dos voltajes de entrada de 1.6 voltios cada uno, y un voltaje de 9 voltios en la entrada 7 (potencia positiva) y 9 voltios en la en la entrada 4 (potencia negativa) 

  ![image](https://user-images.githubusercontent.com/93950169/157093480-3c48c1b0-5442-4bfb-8e6b-d460951fb44e.png)

  Se utiliza el multimetro para medir el voltaje de salida

  ![image](https://user-images.githubusercontent.com/93950169/157093614-ef7e02d5-1193-4e9c-b2cf-95d5e380b4a1.png)

  Se realiza la simulación

  ![image](https://user-images.githubusercontent.com/93950169/157093684-8db8790e-fe4a-4488-846c-b709a6c4f07d.png)

  Se obtiene un voltaje de salida de 3.202 V

  Se procede a la comprobación del voltaje de salida

  ![lagrida_latex_editor (27)](https://user-images.githubusercontent.com/93950169/156978441-fec67585-fc34-4a2b-b2c5-5d421b723769.png)

  ![lagrida_latex_editor (40)](https://user-images.githubusercontent.com/93950169/157095160-007f087c-a857-4b92-8220-bd716e456ba3.png)

  ![lagrida_latex_editor (41)](https://user-images.githubusercontent.com/93950169/157095272-7cbfcd20-5beb-40ab-a91a-879b3b534fb3.png)
  
  Se procede a armar el circuito
  
  ![WhatsApp Image 2022-03-07 at 13 31 52](https://user-images.githubusercontent.com/93950169/157096370-8da4bc3d-eb8a-4b6b-8dad-18f26be2c1b6.jpeg)
  
  ![WhatsApp Image 2022-03-07 at 13 31 53](https://user-images.githubusercontent.com/93950169/157096419-84dc183f-1d9e-45aa-936b-030f332a53a9.jpeg)
  
  ![WhatsApp Image 2022-03-07 at 13 34 45](https://user-images.githubusercontent.com/93950169/157096483-28e7568f-fa68-4d2a-be6a-f72a46780907.jpeg)
  
  ![WhatsApp Image 2022-03-07 at 13 34 45 (2)](https://user-images.githubusercontent.com/93950169/157096705-1608e9af-acfd-4420-8b54-d65b3b3039b4.jpeg)
  
  
5. VIDEO

https://www.youtube.com/watch?v=NS4ZCw_R0MI

6. CONCLUSIONES 

- El amplificador operacional tiene gran cantidad de posibilidades debido a que dispone de diferentes tipos de configuraciones,una de ellas es la configuración como sumador no inversor, en este modo el circuito proporciona a la salida el voltaje de las entradas sumadas. 

- El cáulo teorico coincide con el practico en el momento de la simulación y la fabricaciòn del circuito, se lodró crear un circuito que suma sus dos voltajes de entrada, este metodo llega a ser util al momento de tener entradas variables de voltaje.

7. BIBLIOGRAFÍA

- Youtube.com. 2022. AMPLIFICADORES OPERACIONALES - MODO INVERSOR Y NO INVERSOR SIMULACIÓN EN PROTEUS. [online] Available at: <https://www.youtube.com/watch?v=HMLUjYIFZvI> [Accessed 7 March 2022].

- Gómez, E., 2022. Amplificador sumador de tensión con operacional - Rincón Ingenieril. [online] Rincón Ingenieril. Available at: <https://www.rinconingenieril.es/amplificador-sumador-de-tension/> [Accessed 7 March 2022].

- electronica, W., 2022. Amplificador sumador no inversor. [online] Wilaebaelectronica.blogspot.com. Available at: <https://wilaebaelectronica.blogspot.com/2017/01/amplificador-sumador-no-inversor.html> [Accessed 7 March 2022].
