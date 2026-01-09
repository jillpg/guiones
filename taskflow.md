# 🎬 TaskFlow Analytics - Guion de Grabación (Híbrido)

**Idioma del Audio**: Inglés (Nivel Senior).
**Instrucciones**: Español.
**Duración**: ~2 minutos.

**Preparación**:
1.  Abre **Power BI Desktop** (En la Página 1: Executive Overview).
2.  Abre **VS Code** (En el README.md mostrando el Diagrama de Arquitectura).

---

## 🟢 Escena 1: El Gancho (Contexto de Negocio)
**Visual**: Empieza directamente con el **Dashboard de Power BI (Página 1)** en pantalla completa.
*(Nota: No uses webcam de inicio. Vamos directos al dato).*

**🗣️ Script (Lo que dices en INGLÉS)**:
> "Growth usually looks like a straight line up. But for 'TaskFlow', a B2B SaaS, reality was a flatline.
> Despite increasing traffic, MRR was stagnant.
>
> In this project, I acted as the **Lead Data Engineer and Analyst** to diagnose why.
> My goal wasn't just to build charts, but to engineer an end-to-end pipeline that uncovers the root cause of revenue loss."

---

## 🔵 Escena 2: La Arquitectura (Valor de Ingeniería)
**Visual**: Cambia rápidamente a **VS Code**.
**Acción con el Ratón**:
1.  Muestra el **Diagrama Mermaid** en la previsualización del README.
2.  Señala con el cursor el bloque **'PostgreSQL/Docker'** cuando digas "Docker".
3.  Señala la flecha de **'SQL View'** cuando digas "ELT Pipelines".
*(Opcional: Si eres rápido, muestra 2 segundos el archivo [docker-compose.yml](file:///C:/Users/franc/OneDrive/Escritorio/jillProyectos/TaskFlow_Analytics/docker-compose.yml) para probar que es código real).*

**🗣️ Script (Lo que dices en INGLÉS)**:
> "To solve this, I built a production-grade data stack from scratch.
> I deployed a **PostgreSQL** warehouse using **Docker** to handle the data volume.
>
> Instead of simple CSV loads, I engineered **ELT pipelines** using Python and SQL Window Functions to transform raw transaction logs into a clean, analytical **Star Schema** ready for Power BI."

---

## 🔴 Escena 3: Los Insights (El Análisis)
**Visual**: Vuelve a **Power BI**.

### Parte A: El Incidente (Página 1)
**Acción con el Ratón**:
1.  Haz Zoom o Hover sobre el **pico alto** en el gráfico de líneas de "Churn Rate" (Mes de Marzo).
2.  Mantén el ratón ahí para que se vea el Tooltip con el dato "12%".

**🗣️ Script (Lo que dices en INGLÉS)**:
> "Connecting the model revealed three critical blockers.
> First: **Stability**.
> We see a massive 12% Churn spike in March. By cross-referencing this data with server logs, I correlated this directly to a 4-hour major outage. Reliability is currently our biggest revenue leak."

### Parte B: La Crisis de Brasil (Página 2)
**Acción con el Ratón**:
1.  Haz clic en la pestaña inferior **"2. Growth"**.
2.  Mueve el ratón al Mapa y haz Hover sobre **Brasil** (que debería estar en Rojo).

**🗣️ Script (Lo que dices en INGLÉS)**:
> "Second: **Localization**.
> While the US market is healthy, Brazil is bleeding users.
> The dashboard highlights a churn rate **double** the global average in this region. This signals a breakdown in either the payment gateway or local pricing strategy."

### Parte C: La Verdad de las Cohortes (Página 4)
**Acción con el Ratón**:
1.  Haz clic en la pestaña inferior **"4. Retention"**.
2.  Señala (sin clicar) toda la **fila horizontal de "Marzo 2025"** en la Matriz / Mapa de Calor.
3.  Muestra cómo esa fila es "más roja" que las de arriba.

**🗣️ Script (Lo que dices en INGLÉS)**:
> "And finally, the **Cohort Analysis** confirms the impact.
> You can see this 'red band' in March affecting all user tenures simultaneously. This proves the issue wasn't onboarding quality, but a systemic failure that shook customer trust."

---

## 🟡 Escena 4: La Estrategia (Cierre)
**Visual**: Vuelve a la **Página 1 (Executive Summary)** o muestra una diapositiva final con los 3 puntos clave.

**🗣️ Script (Lo que dices en INGLÉS)**:
> "Data is useless without action. Based on this analysis, I am proposing three immediate steps:
> 1. Audit the Brazilian payment stack.
> 2. Launch a 'Win-back' campaign targeting the specific users lost in March.
> 3. And pivot budget to **Referral acquisition**, which my analysis shows yields a **2x higher LTV** than organic channels.
>
> You can review the full architecture and SQL logic on my GitHub. Thanks."
