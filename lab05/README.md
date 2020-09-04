# Laboratório 05
## Aluno: Lucas Hervatin Trinquinato

# Tarefa 1
![Sub components](https://github.com/lucashtrinquinato/unicamp-inf331/blob/master/lab05/resources/Tarefa%2001.png)

# Tarefa 2
#### Projeto CodePen
#### HTML
```html
<div id="root"></div>
```
#### JavaScript
```javascript
class Barra extends React.Component {
  render() {
    let resultado = "";
    for (let b = 1; b <= this.props.tamanho; b++)
      resultado += "=";
    return resultado;
  }
}

class DinoInfo extends React.Component {
  render() {
    let dinoInfo = <h2> Tiranossauro Rex, 
                        altura 6,1 metros e 
                        peso 14.000 kg
                   </h2>
    return dinoInfo;
  }
}

class Pular extends React.Component {
  constructor(props) {
    super(props);
    this.state = {
      value: null,
    };
  }

  render() {
    return (
      <button className="pular" onClick={() => alert('Pulou a barra!')}> Pular 
        {this.props.value}
      </button>
    );
  }
}

const elemento = <div>
                   <h2>O dino</h2> 
                   <DinoInfo />
                   <Pular />
                   <h1>
                      <Barra tamanho="15" />
                   </h1>
                 </div>
      
ReactDOM.render(elemento, document.getElementById("root"));
```
