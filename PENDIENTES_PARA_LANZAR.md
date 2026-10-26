# Pendientes antes de monetizar o publicar NewRide

Última revisión del repositorio: 20 de octubre de 2026.

La web **sí** identifica al titular con nombre, localidad y correo de contacto, recoge las funciones verificadas de NewRide y dispone de borradores de privacidad, condiciones, aviso legal y solicitud de eliminación. Las páginas no constituyen por sí solas una certificación de cumplimiento legal.

## Requisitos personales y comerciales

- [ ] Decidir si se explotará NewRide como persona física o mediante una sociedad real.
- [ ] Completar en `aviso-legal.html` el NIF que corresponda al prestador y un domicilio/establecimiento legalmente válido, una vez decidido cómo hacerlo público de forma segura. **No inventar estos datos**.
- [ ] Validar con asesoría fiscal el alta censal, Seguridad Social, impuestos y otras obligaciones antes de comenzar la actividad remunerada.
- [ ] Configurar **España como único país de distribución inicial en Google Play Console**. La selección de países se basa en el país de la cuenta de Google Play, no en la posición GPS. Antes de abrir otros mercados, revisar normas, precios e información legal. Evitar bloqueos geográficos injustificados dentro de la UE.

## Tratamiento de datos

- [ ] Verificar las bases jurídicas concretas de cada tratamiento, contratos de encargados, roles de terceros y transferencias internacionales.
- [ ] Comprobar regiones y plazos de copias de seguridad, logs de Supabase, sistemas de autenticación y GitHub Pages. No usar plazos inventados.
- [ ] Revisar el análisis de riesgos sobre ubicación GPS precisa, rutas de trabajo/domicilio y medidas de minimización y seguridad; valorar si procede EIPD.
- [ ] Conservar registros internos de tratamientos, revisar las políticas de RLS y los procesos de ejercicio de derechos.
- [ ] Añadir información básica de privacidad junto al formulario de registro y permitir acceder fácilmente a la política.
- [ ] Implementar, probar y documentar la eliminación de cuenta y datos en la app, así como la vía web y el tratamiento de copias de seguridad.

## Funcionalidades futuras

- [ ] **Premium:** crear y probar el producto comercial, precio real, impuestos, renovación, cancelación, restauración y derechos de consumidores; ajustar las condiciones antes de aceptar pagos.
- [ ] **Anuncios:** elegir red, integrar SDK solo con los permisos necesarios, actualizar privacidad, verificar transferencias y cumplimentar declaraciones en Google Play.
- [ ] **Publicidad EEE/Reino Unido:** integrar una CMP certificada y mecanismos de elección cuando lo exija la tecnología publicitaria utilizada; no activar personalización sin cumplir las normas aplicables.
- [ ] **Google Play:** seleccionar solo España en **Producción → Países/regiones**, establecer público objetivo 18+, declarar ads y Data safety con los datos efectivos, mostrar aviso destacado de GPS en segundo plano y entregar política y URL de eliminación.
- [ ] **Edad:** la casilla 18+ añadida en la app es una autodeclaración, no prueba documental de edad. Confirmar que otros puntos de acceso no eludan la política y ajustar requisitos de tienda.
- [ ] **Web:** sustituir las imágenes de Unsplash por recursos locales si se desea evitar solicitudes de datos técnicos a ese tercero.

## Importante

No introducir DNI, domicilio particular, tokens privados o contraseñas en el historial Git del repositorio público. Si es legalmente necesario hacer públicos algunos datos identificativos, revisar el domicilio de actividad admisible y tomar conscientemente esa decisión antes de incorporarlos.

Fuentes de referencia: [LSSI (BOE)](https://www.boe.es/buscar/act.php?id=BOE-A-2002-13758), [RGPD (EUR-Lex)](https://eur-lex.europa.eu/eli/reg/2016/679/oj), [Google Play: account deletion](https://support.google.com/googleplay/android-developer/answer/13327111?hl=en).
