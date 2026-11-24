# Humanoid Robotics Path 🤖

Ruta de aprendizaje en **robótica humanoide** (control y locomoción + aprendizaje de robots) y preparación para el **Máster Universitari en Automàtica i Robòtica** (UPC – ETSEIB, Barcelona).

**Autor:** Sebastián Ramírez ([@SRamCoding](https://github.com/SRamCoding)) · Chiclayo, Perú
**Inicio:** diciembre de 2026 · **Meta:** empezar el máster en septiembre de 2027

**Leyenda**
- **[M]**: lo cubre un curso obligatorio del máster
- **[M-opt]**: lo cubre una optativa del máster
- **[H]**: específico de humanoides
- **[Base]**: prerrequisito

---

## Progreso

| Fase | Periodo | Carpeta | Estado |
|---|---|---|---|
| 0. Fundamentos | dic 2026 – ene 2027 | [`00-fundamentos`](00-fundamentos/) | ⬜ |
| 1. Señales + Control I | feb – mar 2027 | [`01-senales-control`](01-senales-control/) | ⬜ |
| 2. Robótica I + Modelado + ROS 2 | abr – may 2027 | [`02-robotica-modelado-ros2`](02-robotica-modelado-ros2/) | ⬜ |
| 3. Control moderno + Optimización + Locomoción | jun – jul 2027 | [`03-control-moderno-locomocion`](03-control-moderno-locomocion/) | ⬜ |
| 4. Aprendizaje de robots + Visión | ago 2027 | [`04-aprendizaje-robots-vision`](04-aprendizaje-robots-vision/) | ⬜ |
| RunaSeb v0 (en paralelo) | desde abr 2027 | [`runaseb`](runaseb/) | ⬜ |

---

## PARTE 1: Antes del máster

### Fase 0: Fundamentos [Base]
- Álgebra lineal: 3Blue1Brown *Essence of Linear Algebra* y MIT 18.06 (Strang)
- Ecuaciones diferenciales y números complejos: MIT 18.03 / Khan Academy
- Probabilidad básica
- Python científico: numpy, scipy, matplotlib
- Inglés: preparar IELTS/TOEFL (B2.2)

### Fase 1: Señales + Control I
- **[M] Anàlisi i Processament de Senyals:** *Think DSP* (Downey), Oppenheim *Signals and Systems*
- **[M] Control Automàtic I:** Brian Douglas (YouTube), Ogata, `python-control`
- **Proyecto 1:** PID de posición para un motor DC con encoder (ESP32) + filtrado de un IMU MPU6050

### Fase 2: Robótica I + Modelado + Herramientas
- **[M] Robòtica I:** *Modern Robotics* (Lynch y Park)
- **[M] Identificació i Simulació de Sistemes Dinàmics:** identificar los parámetros del motor del Proyecto 1
- **[M] Eines de Programació:** ROS 2, Gazebo, git, C++ básico
- **Proyecto 2:** pierna o brazo de 2–3 articulaciones en ROS 2/Gazebo con cinemática inversa

### Fase 3: Control moderno + Optimización + Locomoción
- **[M] Control Automàtic II (adelanto):** espacio de estados, LQR, Kalman
- **[M] Optimització en Control i Robòtica:** optimización convexa, CasADi
- **[H] Locomoción con patas:** *Underactuated Robotics* (Tedrake, MIT), *Robot Dynamics* (ETH Zürich). Centro de masa, ZMP, LIPM
- **Proyecto 3:** robot de dos ruedas que se balancea (LQR) + simulación de marcha con LIPM

### Fase 4: Aprendizaje de robots + Visión
- **[M-opt] / [H] Aprendizaje por refuerzo:** *Spinning Up* (OpenAI), Hugging Face Deep RL, MuJoCo / Isaac Lab
- **[H] Aprendizaje por imitación:** LeRobot (Hugging Face)
- **[M] Visió per Ordinador (introducción):** OpenCV
- **Proyecto 4:** humanoide simulado que aprende a caminar con RL

### RunaSeb v0 [H]
Humanoide miniatura (~50 cm). v0: una pierna o un par con servos + ESP32 + IMU + ROS 2. Meta: mantenerse de pie y equilibrarse.

---

## PARTE 2: Durante el máster

| Cuatrimestre | Obligatorias | Optativas sugeridas |
|---|---|---|
| Q1, otoño | Señales, Control I, Eines de Programació, Identificació, Optimització, Robòtica I | – |
| Q2, primavera | Control II, Robòtica II, Tècniques d'IA, Visió per Ordinador | Control Predictiu (MPC), Sistemes Híbrids |
| Q3, otoño | Control III, Robòtica III, Temes Especials en Control, Gestió i Administració | Aprenentatge per Reforç en Robòtica, Sistemes Encastats i de Temps Real |
| Q4, primavera | TFM (15 ECTS) | Prácticas externas (IRI, PAL Robotics…) |

**TFM objetivo:** locomoción humanoide (MPC + RL, sim-to-real).

---

## Hitos administrativos
- [ ] Dic 2026: terminar el grado (Saint Leo) y apostillar el título y las notas
- [ ] Ene–mar 2027: certificado de inglés B2.2
- [ ] 1er trimestre 2027: preinscripción (plazas que se resuelven el 31 de marzo si necesito visado)
- [ ] Después de la admisión: visado y alojamiento

## Notas
- La cobertura de locomoción con patas en Robòtica I–III está por verificar en las guías docentes de la ETSEIB.
- Los periodos de las optativas son del plan 2025.
