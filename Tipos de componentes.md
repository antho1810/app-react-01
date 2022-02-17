Componentes funcionales
function welcome(props){
    return <h1>Hello {props.name}</h1>;
}

Componentes de clase
class Welcome extends React.Component{
    render(){
        return <h1>Hello, {this.props.name}</h1>
    }
}


Componentes funciones 
const Container = () =>{ return (
    <div className = "container">
    <p>Hello</p>
    </div>
);
)}
