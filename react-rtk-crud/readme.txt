ReduxToolkit
//instalacion: npx create-react-app <nombre-del proy>
..borrar archivos inecesarios(app.test.js,report,logo,setuotest )
..npm start 
//manejador de estados con redux
..componentes inicial app creas sus componentes derivadas
el problemas es pasar datos de app con sus derivadas (los otros comp)
pasasr por props da pero la cosas es con comp mas peque;os la derivada a derivada
para eso sol un manejador de estados.
//redux dice un archivo separado hara separado datos guardado
y cualquier componente va poder acceder es centralizar el comp necesario pa todos
de esa forma evita buscar y mas rapido el manejado
//el toolkit simplifica el manejo de la app 
//npm install @reduxjs/toolkit react-redux
..Create a Redux Store
..despues de seguir doc https://redux-toolkit.js.org/tutorials/quick-start
necesitas provider va a contener la app para que la app va llamar a provider
//reducer = es como es redx state
// use dispatch es para funcones qu queremos llamar para actualziar estado
// el use selector es seleccionar o traer algo del estado