# 🧪 Experimento A/A/B - Validación de Nueva Feature

> ¿La nueva imagen de la app realmente aumenta la conversión o solo fue suerte?

🔗 Notebook: [Pega aquí tu link del Notebook]

---

### 🎯 ¿Qué problema de negocio resuelve?

El equipo de diseño queire cambiar las fuentes de la app, pero la gerencia teme que los usuarios sientan este cambio como intimidante.

**Objetivo del análisis:** Determinar mediante prueba de hipótesis si los cambios afectan el indice de conversion de usuarios.

---

### 🔍 ¿Qué hice?

Diseñé y analicé un experimento A/A/B completo:

1.  **Grupo A/A:** Validé que los dos grupos de control son estadísticamente iguales (para asegurar la confiabilidad del experimento)
2.  **Grupo A/B:** Comparé control vs variante con test de significancia estadística
3.  **Calcule p-value, power y tamaño de muestra con SciPy**

**Stack:** Python | SciPy | Stats | Pandas | Matplotlib

---

### 📊 Hallazgos Clave

### No hay diferencia estadísticamente significativa entre los grupos porque todos los valores p son mayores a 0.05.

### Esto significa que:

### Las fuentes nuevas (grupo 248) no mejoraron significativamente las conversiones
### Los grupos de control se comportaron de manera similar entre sí
### La diferencia observada puede deberse al azar, no a un efecto real

---

### 💼 Recomendación

> Como recomendacion queda,revizar el diseño de la pantalla Tutorial, mejorar en ofrecer y anunciar mejores ofertas en la pantalla Offers y si esposible buscar ingresar publicidad o alguna clase de beneficio para quienes despuesde de agregar a Cart vallan directo a Payment

### 👨‍💻 Autor
Cesar R. | Data Analyst Jr. | GDL
