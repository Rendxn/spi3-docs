# Ascensores

Los ascensores deben controlarse mediante un PLC que tenga su propia dirección IP, que esté conectado a un módulo WISE para trabajar con robots MiR o que se pueda controlar a través de un servidor OPC UA. En ascensores más modernos es posible comunicarse a través de su REST API.

Si es necesario, contacte a su distribuidor para más información.

### Registro del Ascensor

Una vez configurado el controlador del ascensor y su dirección IP, se debe registrar en MiR Fleet, así:

1. Ir a `Fleet > Elevators` y seleccione `Create elevator`.
2. Nombre el ascensor, ingresa su dirección IP, selecciona el driver que usa, e indica si el robot debe girar dentro del ascensor. Cuando termines, selecciona `Create elevator`.

    ![Registro de Ascensor en MiR Fleet](../.gitbook/assets/image%20%282%29.png)

3. Seleccione `Floors` para configurar los pisos del ascensor.
