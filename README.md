# VIH-MedEd: Protocolo Clínico para la Identificación y Seguimiento de Pacientes con VIH

Plataforma educativa interactiva diseñada para estudiantes de medicina, médicos internos residentes y profesionales sanitarios, fundamentada en guías clínicas oficiales y literatura médica indexada.

## 📚 Bibliografía de Referencia
1. **NIH HIVinfo**: [Conceptos básicos sobre la infección por el VIH y el SIDA](https://hivinfo.nih.gov/es/understanding-hiv/fact-sheets/vih-y-el-sida-conceptos-basicos)
2. **Elsevier / EIMC**: [Características virológicas del VIH](https://www.elsevier.es/es-revista-enfermedades-infecciosas-microbiologia-clinica-28-articulo-caracteristicas-virologicas-del-vih-S0213005X10004040)
3. **ScienceDirect / GeSIDA**: [Diagnóstico de la infección por el VIH y seguimiento virológico e inmunológico](https://www.sciencedirect.com/science/article/abs/pii/S0213005X10004994)

## 🩺 Funcionalidades Clínicas
- **Algoritmo de Identificación & Diagnóstico:** Flujo interactivo con pruebas de 4.ª generación (Ag p24 + Ac) y diferenciación VIH-1/VIH-2.
- **Calculadora de Estadificación CDC (1993/2014):** Clasificación automática A1-C3 según recuento de linfocitos T CD4 y comorbilidades.
- **Monitoreo Virológico:** Distinción clínica entre "Blip" virológico y fallo virológico con pautas de actuación.
- **Regímenes Preferentes de TAR:** Selección de combinaciones 2 ITIAN + 1 INSTI (Biktarvy, Dovato, Triumeq) con precauciones renales y test genético de HLA-B*5701.
- **Profilaxis de Oportunistas:** Pautas para *P. jirovecii*, *T. gondii* y *Cryptococcus*, además de protocolos PrEP y PEP.
- **Casos Clínicos Aleatorizados:** Banco interactivo de autoevaluación con escenarios reales, analíticas completas y retroalimentación razonada.
- **Biociencias & Estructuras 3D (3Dmol.js):** Visualización cristalográfica de transcriptasa inversa (1REV), proteasa (1HXB), integrasa (3OYA) y gp120/CD4 (1GC1).

## 🚀 Despliegue en GitHub Pages
1. Ve a **Settings** -> **Pages** en tu repositorio de GitHub.
2. En **Build and deployment**, selecciona la fuente **GitHub Actions** o la rama `main` (carpeta `/dist` tras compilar con `npm run build`).
