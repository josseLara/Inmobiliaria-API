# Inmobiliaria-API
Una api sencilla creada con  node.js || express || mysql

```JS
// solicitudes http || ./router
*/esta solicitud HTTP obtiene todas las propiedades mediante el uso del controlador getAllPropiedadesController. Luego, la solicitud envía una respuesta utilizando el controlador getPropiedad.*/
propiedadesRouter.get('/',getAllPropiedadesController,getPropiedad);


propiedadesRouter.get('/:id',getIdPropiedadesController,getPropiedad);: esta solicitud HTTP obtiene una propiedad específica mediante el uso del controlador getIdPropiedadesController. Luego, la solicitud envía una respuesta utilizando el controlador getPropiedad.

propiedadesRouter.post('/agregar',getAddSolvedController);: esta solicitud HTTP agrega una nueva propiedad utilizando el controlador getAddSolvedController.

propiedadesRouter.patch('/:id',patchPropiedadController);: esta solicitud HTTP actualiza una propiedad existente mediante el uso del controlador patchPropiedadController.

propiedadesRouter.delete('/:id',deletePropiedadController);: esta solicitud HTTP elimina una propiedad existente mediante el uso del controlador deletePropiedadController.
