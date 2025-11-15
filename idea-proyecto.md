# Idea de proyecto: Aplicación web para dividir gastos

El cliente necesita una aplicación web que permita a un grupo de amigos registrar y equilibrar los gastos compartidos de una salida. Cada participante puede registrar los gastos que paga (entradas al cine, comida, transporte, etc.) y la aplicación debe:

1. Calcular el total de los gastos registrados.
2. Dividir el total entre el número de personas participantes.
3. Determinar cuánto ha aportado cada persona.
4. Calcular cuánto debe pagar o recibir cada participante para que todos terminen aportando la misma cantidad.

### Ejemplo proporcionado
- Total de gastos: 1200 pesos.
- Número de personas: 6.
- A cada persona le corresponde aportar: 200 pesos.

Pagos realizados:
- Persona A paga entradas por 400 pesos → ya aportó 200 pesos de más, por lo que no debe pagar nada y los demás deben reembolsarle 200.
- Persona B paga comida por 300 pesos → aportó 100 pesos de más, por lo que debe recibir 100.
- Personas que no aportaron dinero → deben cubrir las diferencias que necesitan las personas A y B hasta que todos hayan aportado 200 pesos.

La aplicación debe generar las instrucciones de pagos entre los miembros del grupo para equilibrar las aportaciones.
