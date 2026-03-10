# Práctica Nro. 3: Aplicación del software EES en Motores de Combustión Interna
**Asignatura:** Termodinámica de Máquinas Térmicas (EM6P2A3)  
**Maestría en Ingeniería Automotriz** - Universidad Nacional de Loja  
**Autor:** GRUPAL
**Fecha de Ejecución:** 7 de marzo de 2026

---

## 1. Descripción del Proyecto
Este repositorio contiene el modelado termodinámico y geométrico de un motor de encendido provocado (MEP) desarrollado en el software **Engineering Equation Solver (EES)**. El objetivo principal es el análisis de curvas multiparamétricas y la sensibilidad del desempeño ante variaciones de cilindrada, relación de compresión y condiciones atmosféricas.

## 2. Archivos del Repositorio
*   `Simulacion_Motor.EES`: Archivo fuente original ejecutable en EES Profesional.
*   `Codigo_Fuente.txt`: Copia en texto plano de las ecuaciones implementadas para revisión rápida.
*   `/Resultados`: Carpeta con capturas de las tablas paramétricas y gráficas generadas.

## 3. Parámetros de Diseño del Motor Modelado
*   **Tipo:** 4 tiempos, 4 cilindros.
*   **Geometría:** Diámetro 89.6 mm | Carrera 91 mm.
*   **Relación de Compresión Base:** 10:1.
*   **Potencia Nominal:** 94.57 kW a 4500 rpm.
*   **Combustible:** Gasolina (AFR = 14.5).

## 4. Casos de Estudio Implementados
1.  **Variación de Cilindrada (±25%):** Análisis del impacto del volumen unitario ($V_h$) sobre la potencia y el flujo másico.
2.  **Sensibilidad de la Cámara de Combustión (±15%):** Influencia del volumen muerto ($V_c$) en la relación de compresión recalculada.
3.  **Corrección Atmosférica (Loja):** Modelado del flujo volumétrico de aire según la densidad ambiental (Presión y Temperatura).

## 5. Resultados Gráficos (Simulación EES)
![figura3](https://github.com/user-attachments/assets/d7a0926f-fc80-4060-8299-2350ce88cf8c)
![figura2](https://github.com/user-attachments/assets/74c88f3c-6764-4dcb-8c0e-25ca97372d6d)
![figura1](https://github.com/user-attachments/assets/78a9f95d-0347-4e0b-8b59-77f3edc94c7c)
![figura5](https://github.com/user-attachments/assets/1055b62f-0292-4b54-aa64-e7cc5f26feef)
![figura4](https://github.com/user-attachments/assets/15d8de90-968e-4a70-9943-2af5a4a84fbf)
![figura9](https://github.com/user-attachments/assets/736c515e-9840-4652-bec5-bfaba3e81372)
![figura8](https://github.com/user-attachments/assets/dd4cf5a6-6a75-4b2e-a9f5-44cbc8e0376f)
![figura7](https://github.com/user-attachments/assets/91004525-a0cf-4400-ada5-767d4d3e5b3c)
![figura6](https://github.com/user-attachments/assets/4dfe0c0d-4cc0-4d07-b510-ecea7fdb9df0)
![figura11](https://github.com/user-attachments/assets/81b3338f-2595-4f71-b997-006bea2f0034)
![figura10](https://github.com/user-attachments/assets/9c3e03d6-e63d-47f8-b399-9eec56e385c2)



---
*Documentación generada para la Práctica de Laboratorio Nro. 3 - 2026.*
