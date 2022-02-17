const welcome = <h1>Hello world!</h1>

Por que usarlo?
- Legibilidad
- Logica de renderizado 
- Unificar empaquetado

Un ejemplo de uso:
const name: "Anthony"
const welcome = <h1>Hello World!, {name}</h1>;

JSX como expresión
function getUserNAme(name){
    if(name){
        return <h1>Hello, {formatName(name)},</h1>
    }
    return <h1>Hello, anonymous</h1>
}

Expecificando atributos
const elementos = <div classname="header"/>
const image = <img src={name.urlImage} alt={name}/>