# Pruebas Bootstrap

Resumen

## Referencias
### Link IA:
* [Grok](https://x.com/i/grok?conversation=1919870992362446914)

### Link's Bootstrap:
* [border](https://getbootstrap.com/docs/5.3/utilities/borders/)
* 

## Clases Bootstrap
* `text-center` `text-end` : Centrar texto.
* `.container-fluid`: Ancho completo.
* `border border-3 border-info`: Bordes.

## Notas
* `overflow: hidden;` usarlo dentro de cada div para que el texto no se desborde al hacer zoom.
* `.row` siempre va dentro de `.container`.
* `.row` usa flexbox por defecto, se puede usar `justify-content-center` y ` align-items-center`.
* `col` no es flexbox.
* No anidar `.row` directamente, usar `.col` y dentro `.row`.
* 


## Style .css
* Para editar Bootstrap:
```css
.container {
  max-width: 960px;
}

.col-4 {
  background-color: #f8f9fa;
  border: 1px solid #187fe6;
  text-align: center;
  padding: 15px;
  overflow: hidden;
}

.col-md-4 {
  background-color: #f8f9fa;
  border: 1px solid #187fe6;
  text-align: center;
  padding: 15px;
  overflow: hidden;
}
```
