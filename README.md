    A[Inicio] --> B[Acreedor acude al BANCO FUMEXPO INTERNACIONAL 2024]
    B --> C{¿Tiene talón de canje?}
    C -->|Sí| D[Intercambiar talón por FUNEPESOS]
    C -->|No| E[Termina el proceso]
    D --> F[Visitante realiza compras con FUNEPESOS]
    F --> G[Al finalizar el evento]
    G --> H[EXPOSITOR entrega FUNEPESOS en el BANCO]
    H --> I[EXPOSITOR recibe orden de pago]
    I --> J[EXPOSITOR envía factura dentro de 10 días hábiles]
    J --> K{¿Factura enviada correctamente?}
    K -->|Sí| L[Transferir fondos al EXPOSITOR en 15 días hábiles]
    K -->|No| M[Solicitar corrección y reenvío de factura]
    L --> N[Fin del proceso]
    E --> N
    M --> J
