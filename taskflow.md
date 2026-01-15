# 🎬 Guion de Video: TaskFlow Analytics (Versión Portfolio "High Impact")

**Objetivo:** Enganchar al reclutador/cliente en los primeros 10 segundos. Demostrar "Business Value" + "Technical Mastery".
**Duración:** ~2:30 minutos.
**Formato:** Audio en **INGLÉS** (Texto citado) | Instrucciones en **ESPAÑOL**.

---

### 0:00 - 0:35 | La Introducción: El Problema de Negocio

**Visual (Cámara):**

* **Plano:** Tú hablando a cámara. Plano medio corto. Ropa "Smart Casual" (Camisa o Polo liso). Fondo ordenado.
* **Acción:** Mira a la lente, no a tu pantalla. Sonrisa profesional al presentarte, pero cara seria al hablar del problema.

**Audio (English):**
> "In the B2B SaaS industry, relying on averages is a dangerous game. A company can look healthy on the surface while hidden churn bleeds its revenue dry.
>
> Hi, I’m [Tu Nombre].
>
> In this project, **TaskFlow Analytics**, I simulated the role of a Lead Data Engineer and Analyst for a Task Management SaaS.
>
> My objective wasn't just to build a pretty dashboard. It was to build an end-to-end data pipeline to solve a specific business problem: **Why is our MRR stagnating despite acquiring new users?**"

---

### 0:35 - 1:10 | La Ingeniería: "Full Stack Data" (Python & SQL)

**Visual (Screencast):**

* **0:35:** Muestra VS Code. Archivo `data_generator.py` (Líneas 23-25 donde defines la estacionalidad). **Señala con el cursor** la lista de pesos `month_weights`.
* **0:45:** Cambia rápido a `docker-compose.yml` para mostrar la infraestructura.
* **0:55:** Muestra el SQL `master_view.sql` (alguna CTE compleja o Window Function). **Subraya con el cursor** una función de ventana `PARTITION BY`.

**Audio (English):**
> "Real insights start with reliable engineering.
>
> I built a complete local data warehouse using **Docker** and **PostgreSQL**.
>
> Instead of using static datasets from Kaggle, I wrote a **Python** script to generate 5,000 synthetic users. But I went deeper—I programmed specific seasonality curves and weighted behavioral patterns to mimic real-world business chaos, ensuring the data wasn't just random, but *realistic*.
>
> For the transformation layer, I bypassed simple drag-and-drop tools and performed the heavy lifting directly in **SQL**, utilizing Window Functions to calculate complex Cohort Retention metrics at the database level."

---

### 1:10 - 1:50 | El Hallazgo Clave: "The Brazil Anomaly"

**Visual (Screencast - Power BI):**

* **1:10:** Muestra el Dashboard "Executive Overview".
* **1:20:** Haz click en la página "Growth Engine".
* **1:25:** Haz **ZOOM IN** (o señala con el mouse) en el mapa sobre Brasil y su barra roja de Churn.
* **1:35:** Vuelve rápidamente el mouse al KPI de Churn Rate Global (0.77%) para contrastar.

**Audio (English):**
> "Now, let’s look at the results.
>
> At a high level, the company looks healthy with a **0.77% monthly churn rate**.
>
> However, by drilling down into the geospatial data, I uncovered a major inefficiency. Look at **Brazil**.
>
> While it is a top-3 region for user acquisition, it suffers from a Churn Rate of **1.61%**. That is nearly **three times higher** than the US average.
>
> This insight reveals a clear strategic misalignment: we are acquiring users effectively in LATAM, but failing to retain them—likely due to a lack of localized pricing."

---

### 1:50 - 2:20 | La Solución: "The Month-2 Cliff"

**Visual (Screencast - Power BI):**

* **1:50:** Ve a la página "Retention & Cohorts".
* **2:00:** Mueve el mouse sobre el gráfico de barras "Churn by Tenure". Quédate sobre la barra más alta (Mes 2).

**Audio (English):**
> "Finally, I analyzed *when* we lose these customers.
>
> Through Cohort Analysis, I identified the **'Month-2 Cliff'**.
>
> As you can see, the highest drop-off doesn't happen immediately—it happens between Day 30 and Day 60.
>
> This finding changes our roadmap. It tells us we need to shift Customer Success resources to intervene specifically at the **45-day mark**. Closing this retention gap would significantly improve our LTV, which currently lags behind predictions."

---

### 2:20 - 2:40 | Cierre: Llamada a la Acción

**Visual (Cámara):**

* **Plano:** Vuelve a Ti. Plano medio.
* **Acción:** Al decir "repository below", **señala físicamente hacia abajo** con la mano. Sonrisa de cierre.

**Audio (English):**
> "TaskFlow Analytics demonstrates my ability to own the entire data stack: from writing the Python generation scripts to delivering strategic business recommendations.
>
> You can explore the full code, including the SQL queries and the Power BI file, in the repository linked below.
>
> Thanks for watching."
