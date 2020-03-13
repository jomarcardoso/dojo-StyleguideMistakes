# Erros de um guia de estilos

Alguns caminhos ruins ao criar um guia de estilos

## Implementações

### Resets

Os resets devem tirar tudo do elemento, assim o estilo fica todo ao cargo do componente.

```html
<button class="icon">
  Não quero a aparência de botão aqui
</butoon>
```

```css
.icon {
  width: 100%;
  max-width: 30px;
  background: transparent; // remover o background do botão
  padding: 0; // remover o padding do botão
  border: 0; // remover o padding do botão
}
```

Nenhuma das propriedades acima é do icon.

### Botões

Fazer a largura com padding. **Problema:** não responsivo.

Usar o padding apenas para não colar o conteúdo.
