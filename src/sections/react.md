<!-- .slide: data-background="static/img/react-background.png" data-background-transition="zoom" -->

----

React es una _librería Javascript focalizada en el desarrollo de interfaces de usuario_.

<small>
Así se define la propia librería y evidentemente, esa es su **principal área de trabajo**. Sin embargo, lo cierto es que en React encontramos un excelente aliado para hacer todo tipo de aplicaciones web, SPA (_**Single Page Application**_) o incluso aplicaciones para móviles.
Para ello, alrededor de React existe un completo ecosistema de _módulos_, _herramientas_ y _componentes_ capaces de ayudar al desarrollador a cubrir objetivos avanzados con relativamente poco esfuerzo.
</small>

----

React representa una base sólida sobre la cual se puede **construir casi cualquier cosa con Javascript**.

----

**Ejemplo de una componente renderizable en react**

```jsx
import React, { Component } from 'react'
import ReactDOM from 'react-dom'

class App extends Component {
    render() {
        return (
            <div>
                Soy un ejemplo hecho en react :D
            </div>
        )
    }
}

const rootElement = document.getElementById('root')
ReactDOM.render(<App />, rootElement)
```
<!-- .element: contenteditable="true" -->
