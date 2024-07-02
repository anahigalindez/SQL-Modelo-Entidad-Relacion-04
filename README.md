# Paso a paso:

Identificar las entidades principales: **Cliente**, **Reserva**, **Coche**, **Garaje** y **Agencia**.
   
  - **Cliente:**
     - ClienteID **(PK)**
     - Nombre
     - Apellido
     - Direccion
     - Telefono
    
  - **Reserva:**
     - ReservaID **(PK)**
     - Fecha_Comienzo
     - Fecha_Terminacion
     - ClienteID **(FK)**
     - AgenciaID **(FK)**
   
  - **Coche:** 
     - CocheID **(PK)**
     - Marca
     - Patente
     - ReservaID **(FK)**
     - NumeroGaraje **(FK)**
     - AgenciaID **(FK)**
   
  - **Garaje:**
    - GarajeID **(PK)**
    - NumeroGaraje

  - **Agencia**
    - AgenciaID **(PK)**
    - Nombre
    - Direccion
    - Telefono
  
