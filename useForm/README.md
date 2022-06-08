# useForm

Ejemplo:
```
    const initalState = {
        name: '',
        age: 0,
        email: '',
    }
    const [ formState, handleInputChange, reset ] = useForm( {initialState} );
```