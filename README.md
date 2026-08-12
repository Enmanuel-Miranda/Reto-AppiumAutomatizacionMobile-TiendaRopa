# Automatizacion Mobile - QA Innovation Lab

Proyecto de automatizacion Mobile

---
##Tecnologias y herramientas utilizadas

* **Java**
* **Maven**
* **Appium** y **Appium Inspector**
* **Selenium**
* Android SDK / Emulador**

---
## Estructura del Proyecto
```text
QAInnovationLab/
│
├── src/
│   ├── test/
│   │   ├── java/
│   │   │   ├── com/nttdata/
│   │   │   │   ├── runners/          # Ejecutores de Cucumber
│   │   │   │   ├── screens/          # Localizadores y acciones de pantallas (POM)
│   │   │   │   ├── steps/            # Lógica de los pasos de pruebas
│   │   │   │   └── stepsdefinitions/ # Conexión entre los Features y los Steps
│   │   │   └── ...
│   │   └── resources/
│   │       └── features/             # Archivos .feature (Escenarios BDD)
│   
└── pom.xml                           # Dependencias del proyecto (Maven)
```


