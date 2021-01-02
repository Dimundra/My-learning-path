# Learnign React
## Basic concepts

1. ### **`Class Component` may contain such methods**:
    - **`constructor()`** (`argument`: variable that will be bounded to the inherited properties) contain:   
      - a) - `this.state` object - a JavaScript object that stores a component’s dynamic data and determines the component’s behaviour.
      <br><br>
      `this.setState()` allow us to update the value of this object(`this.setState({"key": "value"})` || `this.setState(function(state, props) { return ...})` || `this.setState((state, props) => ...)`) - can update single property of state or multiple of them, so this method does'n replace but merge properties.
    - **`componentDidMount()`** - method which executes after component rendered.
    - **`componentWillUnmount()`** - method which executes after component removed from DOM three.
