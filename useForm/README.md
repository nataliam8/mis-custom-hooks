# useForm

Ejemplo de uso:
```
    const initialForm = {
        nombre: '',
        edad: 0,
        email: ''
    };
    
    const [ formValues, handleInputChange, reset ] = useForm( initialForm );
```