# Keylogger (script de ejemplo)

> **AVISO IMPORTANTE — LEE ANTES DE USAR**  
> Este repositorio contiene un **script de registro de teclas** (keylogger). Estos programas pueden **violar la privacidad** y la ley si se usan para obtener datos de otras personas sin su consentimiento explícito.

---

## Descripción
Pequeño script en Python que registra las teclas presionadas y las guarda en `archivo.txt`. El programa finaliza cuando se presiona la tecla `ESC`.

---

## Requisitos
- Python 3.7 o superior instalado.
- Paquete Python: `keyboard`.

> En Windows la captura global de teclas suele requerir permisos elevados (ejecutar como Administrador). Ejecuta con permisos elevados **solo** si entiendes los riesgos y estás en un entorno controlado.

---

## Instalación
Instala la dependencia con el intérprete de Python que uses para ejecutar el script:

```bash
pip install -r requirements.txt