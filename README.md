# Cuenta tu texto

Soy Serch, de CyberSerchMX. Quise revisar la extensión de un texto sin pegarlo en un servicio externo.

Este proyecto forma parte de mi práctica como ingeniero en diseño de software y redes y entusiasta de la ciberseguridad. Estoy reuniendo ejercicios que ya tenía y utilidades nuevas en repositorios pequeños, con un objetivo concreto y límites visibles. No presento esta muestra como un trabajo contratado ni como un resultado de clientes.

## Para qué lo uso
Cuenta puntos de código Unicode, palabras y tiempo estimado de lectura; admite acentos y números.

## Cómo probarlo
Abre index.html. Prueba con: node --test tests/app.test.cjs

## Qué revisé al construirlo
Separé la lógica de la interfaz o de la entrada de archivos para probar los casos de error. Mi enfoque de seguridad es reducir permisos y dependencias, validar datos antes de trabajar con ellos y no prometer más de lo que el código hace.

**Nivel:** Básico. Las pruebas incluidas son reproducibles; no equivalen a una auditoría independiente.

## Límites y siguiente paso
Los caracteres son puntos de código: un emoji compuesto puede contar varias unidades. La lectura usa 200 palabras/minuto, no una medición personal. No guarda al recargar.

No incluyas credenciales ni datos reservados en incidencias públicas. El repositorio no incorpora analítica. Código publicado para consulta; no se concede una licencia adicional de reutilización.

— Serch · [CyberSerchMX](https://github.com/sergioh-devsec)
