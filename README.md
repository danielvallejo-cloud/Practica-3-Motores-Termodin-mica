# Práctica Nro. 3: Aplicación del software EES en Motores de Combustión Interna
**Asignatura:** Termodinámica de Máquinas Térmicas (EM6P2A3)  
**Maestría en Ingeniería Automotriz** - Universidad Nacional de Loja  
**Autor:** GRUPAL

---

## 1. Descripción del Proyecto
Esta web contiene el modelado termodinámico y geométrico de un motor de encendido provocado (MEP) desarrollado en el software **Engineering Equation Solver (EES)**. El objetivo principal es el análisis de curvas multiparamétricas y la sensibilidad del desempeño ante variaciones de cilindrada, relación de compresión y condiciones atmosféricas.

## 2. Archivos del Repositorio
*   [📥 **Descargar Ejercicio 1.EES**](./Ejercicio%201.EES) - Resolución del motor de 1360 cm³ (Banco de ensayos y condiciones de Loja).
*   [📥 **Descargar Ejercicio 2.EES**](./Ejercicio%202.EES) - Análisis paramétrico y de sensibilidad (Variación de Vh y Vc).
*   [📄 **Ver Codigo_Fuente.txt**](./Ejercicio%202.txt) - Respaldo en texto plano de las ecuaciones implementadas.

## 3. Parámetros de Diseño del Motor Modelado
### Motor del Ejercicio 1 (Ensayo de Banco y Corrección Atmosférica)
*   **Cilindrada Total:** 1360 $cm^3$
*   **Geometría:** Diámetro 75 mm | Carrera 77 mm.
*   **Relación de Compresión:** 9.5:1.
*   **Potencia Nominal:** 55 kW a 6000 rpm.
*   **Par Motor Máximo:** 122 N·m a 4000 rpm.
*   **Volumen Unitario (Vh):** 340 $cm^3$
*   **Volumen de Cámara (Vc):** 40 $cm^3$

### Motor del Ejercicio 2 (Análisis Paramétrico y Sensibilidad)
*   **Tipo:** 4 tiempos, 4 cilindros.
*   **Geometría:** Diámetro 89.6 mm | Carrera 91 mm.
*   **Relación de Compresión Base:** 10:1.
*   **Potencia Nominal:** 94.57 kW a 4500 rpm.
*   **Volumen Unitario (Vh):** 573.75 $cm^3$
*   **Volumen de Cámara (Vc):** 63.75 $cm^3$
*   **Combustible:** Gasolina (AFR = 14.5).

## 4. Casos de Estudio Implementados
### Ejercicio 1: Análisis de Desempeño y Corrección Atmosférica (Motor 1.36L)
1.  **Evaluación en Banco de Ensayos:** Cálculo de la potencia efectiva ($N_e$) y consumo específico ($C_e$) a partir de datos experimentales de par y tiempo de consumo.
2.  **Modelado de Corrección Atmosférica (Loja):** Aplicación del factor de corrección $k$ para determinar la pérdida de prestaciones (par y potencia) debido a la baja presión barométrica ($595\ mmHg$) y temperatura de la ciudad de Loja.
3.  **Análisis de Elasticidad:** Determinación de los coeficientes de par, velocidad y elasticidad total para evaluar la flexibilidad operativa del motor.

### Ejercicio 2: Análisis de Sensibilidad Geométrica y Paramétrica (Motor 2.3L)
1.  **Variación de Cilindrada Unitaria (±25%):** Simulación del impacto del volumen desplazado ($V_h$) sobre el escalamiento de la potencia efectiva y el flujo másico de combustible ($C_h$).
2.  **Sensibilidad del Volumen de Cámara (±15%):** Estudio de la variación crítica en la relación de compresión recalculada ($r_c$) al modificar el espacio muerto de la culata ($V_c$).
3.  **Modelado de Flujo Volumétrico:** Análisis de la relación inversa entre la densidad del aire ambiental y el volumen de aspiración requerido por el motor para mantener la estequiometría.

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
