# Proyecto de Fabricación y Diseño de PCB con CNC y FlatCAM

## Descripción

Este proyecto proporciona una guía detallada para el diseño y fabricación de Placas de Circuito Impreso (PCB) utilizando una máquina CNC. Incluye todo el proceso, desde el diseño en KiCad, la generación de G-codes con FlatCAM, hasta la configuración de la máquina CNC, fresado, taladrado, soldadura y pruebas de continuidad, con un enfoque en seguridad y precisión.

## Tecnologías Utilizadas

- **KiCad**: Software libre de diseño de circuitos y PCB.
- **FlatCAM**: Herramienta para la generación de G-codes a partir de archivos Gerber.
- **CNC**: Máquina para fresado, taladrado y corte de PCBs.
- **Git LFS**: Sistema de almacenamiento de archivos grandes para gestionar archivos pesados.

## Instalación

### KiCad

1. Descargar e instalar [KiCad](https://kicad.org).
2. Crear un nuevo proyecto y diseñar tu circuito en el Editor de Esquemas y Editor de PCB.

### FlatCAM

1. Descargar e instalar [FlatCAM](https://flatcam.org).
2. Importar archivos Gerber y Drill desde KiCad.
3. Generar G-code para la CNC.

## Pasos del Proyecto

1. **Diseño de Circuito en KiCad**
   - Crear el esquema eléctrico y diseño de PCB.
   - Exportar los archivos Gerber.

2. **Generación de G-code con FlatCAM**
   - Importar archivos Gerber y Drill.
   - Configurar la CNC y generar los archivos G-code para fresado y taladrado.

3. **Fabricación de PCB con la CNC**
   - Fijar la PCB a la máquina CNC.
   - Fresar, taladrar y cortar el diseño de la PCB.

4. **Soldadura y Pruebas**
   - Limpiar la PCB después del fresado.
   - Soldar los componentes y realizar pruebas de continuidad.

## Prácticas de Seguridad

- Usar gafas de seguridad al trabajar con la CNC.
- Asegurarse de que la placa esté bien sujeta antes de iniciar el fresado.
- No manipular la máquina mientras está en movimiento.

## Contribuciones

Si deseas contribuir a este proyecto, por favor sigue estos pasos:
1. Haz un fork de este repositorio.
2. Crea una nueva rama (`git checkout -b mi-nueva-rama`).
3. Realiza tus cambios y haz commit (`git commit -am 'Agregué una nueva característica'`).
4. Haz un push a tu rama (`git push origin mi-nueva-rama`).
5. Abre un Pull Request.

## Link software: https://drive.google.com/drive/folders/1fUbaWD3XvxiLQ4gRuyqp59L4k9Gw1fmp?usp=drive_link
