# Inmobiliaria-API
Una api sencilla creada con  node.js || express || mysql

```JS
// solicitudes http || ./router
propiedadesRouter.get('/',getAllPropiedadesController,getPropiedad);

propiedadesRouter.get('/:id',getIdPropiedadesController,getPropiedad);: esta solicitud HTTP obtiene una propiedad específica mediante el uso del controlador getIdPropiedadesController. Luego, la solicitud envía una respuesta utilizando el controlador getPropiedad.

propiedadesRouter.post('/agregar',getAddSolvedController);
propiedadesRouter.patch('/:id',patchPropiedadController);: 

propiedadesRouter.delete('/:id',deletePropiedadController);

```

* '/' = Esta solicitud HTTP obtiene todas las propiedades mediante el uso del controlador getAllPropiedadesController. Luego, la solicitud envía una respuesta utilizando el controlador getPropiedad.
* '/agregar' = Esta solicitud HTTP agrega una nueva propiedad utilizando el controlador getAddSolvedController.
* patch('/:id') = Esta solicitud HTTP actualiza una propiedad existente mediante el uso del controlador patchPropiedadController.
* delete('/:id') = Esta solicitud HTTP elimina una propiedad existente mediante el uso del controlador deletePropiedadController.
