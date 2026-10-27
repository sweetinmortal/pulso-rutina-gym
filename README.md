# Pulso · Rutina de gym

Rutina interactiva de tres días para consultar desde el teléfono mientras entrenas. Todo está integrado en un único archivo HTML: diseño adaptable, JavaScript y animaciones SVG. Funciona sin conexión y sin instalar dependencias.

## Cómo usarla

1. Descarga este repositorio como ZIP y extrae su contenido.
2. Abre [pulso-rutina-gym.html](pulso-rutina-gym.html) en tu navegador.
3. Elige un día, consulta los ejercicios y marca las series completadas.

La rutina incluye alternativas seleccionables, calentamientos, indicaciones de técnica, repeticiones por serie y un temporizador con descansos según el ejercicio. Puedes pausar, reiniciar o sumar tiempo al descanso.

Cada ejercicio tiene un único campo de **peso máximo** con texto libre, por ejemplo `40 kg` o `90 lb`. Se conserva entre sesiones y se comparte cuando eliges el mismo ejercicio en otro día. Las alternativas guardan su propia referencia.

Al cambiar la fecha del dispositivo se desmarcan las series y los calentamientos; se conservan las referencias de peso y las sesiones guardadas.

## Datos y respaldos

Los registros se guardan con `localStorage` en el navegador y dispositivo donde entrenas. No hay cuentas, servidor de datos, analítica ni sincronización automática. Los enlaces de referencia se abren solo si los seleccionas.

El HTML no incluye tus registros personales. Para hacer una copia de ellos usa **Ajustes → Exportar datos**; puedes restaurarla con **Importar datos**. El respaldo JSON es independiente del archivo HTML y puede contener tus pesos, notas e historial.

Las ilustraciones son orientativas. Las indicaciones de cada ejercicio se consultan en **Ver técnica** y en la **Guía**.

## Contenido del repositorio

- `pulso-rutina-gym.html`: aplicación completa y autocontenida.
- `README.md`: esta guía de uso.
