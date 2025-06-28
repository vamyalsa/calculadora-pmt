# Calculadora de Cuota - Vamyal S.A.

Una calculadora web simple para calcular cuotas de préstamos.

## Descripción

Esta aplicación web permite calcular cuotas mensuales de préstamos utilizando la API de Vamyal S.A. La interfaz es responsiva y soporta modo oscuro.

## Características

- Calculadora de cuotas de préstamos
- Interfaz responsiva con Tailwind CSS
- Soporte para modo oscuro
- Validación de datos de entrada
- Integración con API externa

## Uso

### Desarrollo Local
1. Abre `index.html` en tu navegador
2. Ingresa el capital del préstamo
3. Ingresa el plazo en meses
4. Haz clic en "Calcular" para obtener la cuota mensual

### Docker
```bash
# Construir imagen
docker build -t calculadora-pmt .

# Ejecutar container
docker run -p 8080:80 calculadora-pmt
```

Accede en: http://localhost:8080

## Tecnologías utilizadas

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (Vanilla)
- API REST
- Docker
- Nginx

## Licencia

© 2025 Vamyal S.A.