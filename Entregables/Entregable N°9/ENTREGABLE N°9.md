## ENTREGABLE N°9

1. **VERIFICACIÓN DE DISEÑO (SOFTWARE)**  
     
   Aplicación para monitorear el correcto uso del bastón a partir de la fuerza  
   

|  Funciones | Cumplimiento |  |
| ----- | :---: | :---: |
|  | Si | No |
| Permite ingresar valores | X |  |
| Realiza el cálculo del rango de fuerza límite a partir del peso |  | X |
| Registra los datos históricamente |  | X |
| Tiene un login para los usuarios | X |  |
| A partir de la fuerza medida categoriza el resultado/movimiento (correcto o incorrecto) | X |  |

   

   

2. **VERIFICACIÓN DE DISEÑO (HARDWARE)**  
     
   **Preguntas claves**  
   Sistema de medición de fuerza a través de sensores  
     
* **¿Cuánto peso debe tener el dispositivo ?**  
  El dispositivo sumado al bastón debe pesar máximo 100 gramos, esto permite que para el usuario no le resulte incómodo, pesado o molesto al adaptarse al prototipo.

    
* **¿Cuánto es el tiempo que debe durar la batería de forma autónoma?**

  El tiempo que dura la batería es de 2 horas mínimamente.


* **¿Cuánta presión puede soportar el paciente en la parte donde será colocado el dispositivo?**

  El bastón soportará el 20% del peso corporal de la persona


* **¿Con cuantos botones físicos debe contar el dispositivo?**  
  Solo usaremos un botón físico, el cual será el de apagar y prender el dispositivo.  
    
* **¿Qué dimensiones debe tener el dispositivo?**
![plano_case_componentes (2)](https://github.com/user-attachments/assets/82fa2fc4-56f8-4e2d-a5ee-d438a67e4ca2)

**Altura:** 110mm  
**Largo:** 58mm  
**Ancho:** 49mm

![plano_socket2_imprimir](https://github.com/user-attachments/assets/3588470e-e330-49b3-9545-38ec19fb2c65)

**Diámetro externo:** 46mm  
**Diámetro interior:** 40mm

![plano_case (1)](https://github.com/user-attachments/assets/5cc5ac37-33fe-44eb-bba9-793e1e3b81b5)

**Largo:** 55 mm  
**Ancho:** 55 mm  
**Altura:** 45 mm

* **¿Necesita un elemento de visualización?**

  Si, necesita un elemento de visualización para alertar al usuario , usaremos uno táctil, el de vibración

| Requerimiento de Diseño | Resultado del Test |
| ----- | ----- |
| El dispositivo sumado al bastón debe pesar máximo 100 gramos. | En suma todos los componentes electrónicos tienen un peso de 110g (92g PLA, 12g TPU y componentes), esto no representa una alta dificultad en la caminata del usuario. |
| Se debe tener un autonomia de bateria de 2 horas mínimamente.  | Se puso en funcionamiento la medición de sensores con una batería 1000mAh dado una autonomía en bajo consumo de 20 horas y en alto consumo de 2 horas. |
| Se debe tener un solo botón físico en el dispositivo para aumentar la practicidad en su uso. | En este diseño se cuenta con un boton switch que permite al usuario prender y apagar el dispositivo, lo demás se maneja desde la aplicación. |
| Se debe seleccionar un sistema de ajuste que pueda fijar el dispositivo al bastón y pueda contabilizar la fuerza ejercida mientras camina. | En este diseño se utilizó cintillos para sujetar el case al bastón, esto permite que se monitoree el movimiento mediante el sensor de fuerza en la parte inferior. |

**AVANCE DE LA APLICACIÓN**

<img width="565" alt="Captura de pantalla 2024-11-20 a la(s) 00 05 54" src="https://github.com/user-attachments/assets/99a71a80-8526-4e17-aac4-0f1db5f49b8f">
<img width="577" alt="Captura de pantalla 2024-11-20 a la(s) 00 06 00" src="https://github.com/user-attachments/assets/1db9086b-7cbe-4f77-848e-5942f84850a7">
<img width="315" alt="Captura de pantalla 2024-11-20 a la(s) 00 06 05" src="https://github.com/user-attachments/assets/d485c6f2-4abe-411e-b88b-c9b82cf83200">


