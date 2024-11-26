graph TD
    A[Inicio] --> B{¿Pago anticipado?}
    B -- Sí --> C[Registro en expediente]
    B -- No --> Z[No puede ingresar]
    C --> D[Entrega de canasta de insumos]
    D --> E{¿Firma la entrega?}
    E -- Sí --> F[Espera llegada del paciente]
    E -- No --> Y[Proceso detenido]
    F --> G[Paciente sube escaleras]
    G --> H[Inicia el reloj]
    H --> I[Paciente baja escaleras]
    I --> J[Detiene el reloj]
    J --> K[Médico firma tiempo restante]
    K --> L[Fin]
