# Resource Monitor (`resource_mon`) - Monitoreo de CPU y Memoria en Linux

**Docente:** Juan Bernardo Gómez Mendoza  
**Curso:** Programación de Sistemas Linux Embedidos – 2025-1S  
**Fecha de entrega:** 23 de mayo de 2025  

---

## **Integrantes del Equipo**
| Nombre                         | ID         |
|--------------------------------|------------|
| Diego Alejandro Arboleda Cuero | 1087834596 |
|                                |            |
|                                |            |
| Ivonne Tatiana Zapata Martínez | 1002543377 |

---

## **Descripción del Proyecto**
Programa en C que muestra en tiempo real:
- **CPU**: Nombre, fabricante, núcleos, hilos y % de uso por hilo.
- **Memoria**: Física (MB), swap (MB) y % de uso.
- **Interfaz**: Actualización en la misma posición de pantalla (sin scroll).

**Teclas:**
- Presione `q` para salir.

---

## **Estructura del Proyecto**
```plaintext
Resource_Monitor/
├── bin/          # Ejecutables
├── obj/          # Objetos (.o)
├── src/          # Código fuente
│   ├── cpuinfo_manip.{c,h}  # Datos de CPU
│   ├── meminfo_manip.{c,h}  # Datos de memoria
│   ├── tui.{c,h}            # Interfaz
│   └── resource_mon.c       # Programa principal
├── test/         # Pruebas
└── README.md     # Este archivo
