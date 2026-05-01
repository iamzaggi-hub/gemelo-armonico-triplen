# gemelo-armonico-triplen · Análisis de la anomalía 4.2σ (LHCb / CERN)
## DOI / Citable reference
This work has been deposited in Zenodo: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19952835.svg)](https://doi.org/10.5281/zenodo.19952835)

**Gemelo digital para visualización y verificación metrológica de la falla armónica triplen (16.725, 836.25 kHz) identificada en los datos públicos del detector LHCb.**

Este repositorio contiene una implementación HTML/CSS/JS que reproduce las tablas angulares, temporales y de frecuencias derivadas exclusivamente de parámetros abiertos del CERN (apertura de 300 mrad y probabilidad 1/16.000). Su propósito es servir como herramienta de demostración para la auditoría de interferencias electromagnéticas y la corrección de fase (DAC Riemanniano).

---

## 🧭 Origen del proyecto

- **Contexto:** El 9 de abril de 2026, la colaboración LHCb reportó una desviación de 4.2σ (1/16.000) en las desintegraciones B → Kπμμ.
- **Hipótesis tratada:** Error sistemático de origen eléctrico y metrológico.
- **Constante clave descubierta:** ε_CERN = 0.002387324 gon (desfase bidireccional del colimador).
- **Frecuencia crítica:** Armónico triplen de orden 16.725 → 836.25 kHz, generado internamente por variadores de frecuencia del CERN.
- **Referencia oficial:** [PRL aceptado](https://journals.aps.org/prl/accepted/10.1103/24g9-yn9d)

---

## 📊 Contenido del repositorio

| Archivo | Descripción |
|---------|-------------|
| `ARMONICOS_ZAGGI_CERN.HTML` | Visualizador de la falla: tablas con ángulos en gones, tiempos propios, frecuencias y armónicos. |
| `CERN_FAIL_ZAGGI.html` |  Visualizador fLHCb para Anomalía de 4.2σ (1/16.000), implementa de forma didáctica el Informe de datos metrológicos extraídos de parámetros públicos del CERN |
| `LICENSE` | Licencia de uso exclusivo para el CERN (ver más abajo). |
| `README.md` | Este archivo. |
|Certificados-Copyrigth| Registros chilenos de propiedad intelctual registrada en 2024, a nombre de ZAGGI (seudónimo)
|Simuladores| Carpeta con imagenes y simuladores en formato HTML, gemeelos de fallo y aplicación de corrección.
|TSA-Sello de Tiempo| Archivos de certificación y autenticidad de los documentos bajo modelo Time Stamping TSA. (Notario Digital)

---

## 🧪 Uso (solo para verificación interna del CERN)

1. **Clona el repositorio**  
   `git clone https://github.com/iamzaggi-hub/gemelo-armonico-triplen.git`

2. **Abre el archivo** `ARMONICOS_ZAGGI_CERN.HTML` y `CERN_FAIL_ZAGGI.html` en cualquier navegador moderno.

3. **Interactúa con los datos:**  
   - Observa la correspondencia entre apertura, error angular y constante ε_CERN.  
   - Comprueba la relación T₀ × 50 Hz = 2.387325 = 1000·ε_CERN (prueba de acoplamiento con la red de 50 Hz).  
   - Revisa la frecuencia del armónico 16.725 (836.25 kHz) y su clasificación como triplen de secuencia cero.

4. **Si deseas simular la corrección:**  
   - El repositorio no ejecuta código activo por sí mismo; es una maqueta de datos verificados.  
   - La corrección real (DAC Riemanniano y filtro LC) debe implementarse en hardware/FPGA bajo licencia.

---

## ⚖️ Propiedad intelectual y condiciones de uso

- **Titular:** Francisco J. Zapata García (ZAGGI), Kinetic Vision Forensic Lab, Chile.  
- **Registros chilenos:** 2024-A-10366 (Tesis Doctoral) y 2024-A-10500 (Codex Vitalis).  
- **Depósitos internacionales:** Zenodo DOI:10.5281/zenodo.19633231, GitHub (este repositorio con timestamp anterior al anuncio de PRL).  
- **ISSN del laboratorio:** 0710-4349.

**Uso permitido:**  
✔️ Verificación interna, estudios de compatibilidad electromagnética y análisis de datos por parte del CERN.  
✔️ Cita académica con referencia explícita al autor y al repositorio.

**Uso prohibido sin licencia:**  
❌ Implementación operativa en el sistema de adquisición de datos del LHCb.  
❌ Explotación comercial o industrial del método de corrección de fase (DAC Riemanniano) o del diseño de filtros asociados.  
❌ Distribución del código o los datos como si fueran de dominio público.

Para acuerdos de licencia, contactar a: **iamzaggi@gmail.com**.

---

## 📚 Referencias técnicas

- LHCb Collaboration, *Phys. Rev. Lett.* (aceptado), CERN-EP-2026-042 (2026).  
- G. Haefeli et al., *The LHCb DAQ system and the TELL1 board*, CERN-LHCC-2002-002.  
- E. Petroff et al., *Identifying the source of perytons at the Parkes radio telescope*, MNRAS 451, 3933 (2015).  
- IEEE Std 519-2022, *Harmonic Control in Electric Power Systems*.  
- F. J. Zapata García, *Resolución del Problema del Milenio de Navier-Stokes mediante la restauración de la base métrica gónica (400°)*, Zenodo (2026).

---

## 🧠 Autor

**Francisco J. Zapata García (ZAGGI)**  
Ingeniero en Seguridad Industrial, investigador independiente.  
Kinetic Vision Forensic Lab – Chile  
📧 iamzaggi@gmail.com · ORCID: 0009-0004-8127-1933  

*“El tiempo no transcurre: se acumula. Cada día recibimos 56 segundos de eternidad.”*
## DOI / Citable reference

This work has been permanently archived in Zenodo:  
[https://doi.org/10.5281/zenodo.19952835](https://doi.org/10.5281/zenodo.19952835)
