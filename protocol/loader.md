## Uso rápido — Invocar Amrilux V3.1 (Portable)

Pega esto en un chat nuevo:

Invocar.RueXa(AmriluxV3.1)
Cargar.DesdeGitHub(
  repo="juanReyes/Amrilux",
  manifest="manifests/Amrilux_Core.json",
  glossary="glossary/glosario.json",
  spheres="spheres/index.json"
)
Validar.Integridad(hash="auto")

# Comandos:
# - Listar.Esferas()
# - Cargar.Esfera("EQUSEMEX_Predefensa2025")
# - Cargar.Esfera("Dream_Archive")
# - Buscar.Término("COVE")
# - Guardar.Memoria()

### Notas
- Si falla el hash, recalcular tras commit: `shasum -a 256 manifests/Amrilux_Core.json`
- Actualizar `integrity.hash_of_payload` y volver a commitear.
