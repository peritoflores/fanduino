# Ejemplo Básico para Arduino Uno: Encender y Apagar un LED

Este programa básico enciende y apaga un LED conectado al pin 13 del Arduino Uno en intervalos de un segundo. Este es un excelente punto de partida para principiantes.

## Código

```cpp
// El pin 13 ya está conectado al LED integrado en la placa Arduino Uno.
const int ledPin = 13;

void setup() {
  // Configurar el pin 13 como salida
  pinMode(ledPin, OUTPUT);
}

void loop() {
  // Encender el LED
  digitalWrite(ledPin, HIGH);
  delay(1000); // Esperar 1 segundo (1000 milisegundos)

  // Apagar el LED
  digitalWrite(ledPin, LOW);
  delay(1000); // Esperar 1 segundo
}
```

## Material Necesario
- Arduino Uno
- Cable USB para conectar el Arduino a tu computadora
- (Opcional) Un LED externo y una resistencia de 220 ohm si deseas usar otro pin.

## Pasos para Subir el Código
1. Conecta tu Arduino Uno a tu computadora usando el cable USB.
2. Abre el software de Arduino IDE.
3. Copia y pega el código en el editor.
4. Selecciona la placa "Arduino Uno" en el menú de herramientas.
5. Selecciona el puerto al que está conectado el Arduino.
6. Haz clic en el botón de subir para cargar el código al Arduino.

Una vez que el código se haya subido exitosamente, deberías ver el LED en el pin 13 encendiéndose y apagándose en intervalos de un segundo.

¡Diviértete experimentando con Arduino!