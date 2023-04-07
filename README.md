# Inmobiliaria-API
Una api sencilla creada con  node.js || express || mysql

```JS
// solicitudes http || ./router
propiedadesRouter.get('/',getAllPropiedadesController,getPropiedad);
propiedadesRouter.get('/:id',getIdPropiedadesController,getPropiedad);
propiedadesRouter.post('/agregar',getAddSolvedController);
propiedadesRouter.patch('/:id',patchPropiedadController);
propiedadesRouter.delete('/:id',deletePropiedadController);
