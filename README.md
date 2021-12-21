# Neumorphism_Form

# Installation :

1. Copy the neumorph_form folder in your repo.
2. Add neumorphism as a dependency in your package.json file.

```json
{
  "dependencies": {
    "neumorphism": "file:../neumorph_form"
  }
}
```

# Note :

Add this css snippet when passing input or button through slot .

```css
button, input{
    width: 100%;
    height: 100%;
    background-color:transparent;
    text-color: black;
}
```

# Form

<img src="sample_images/form.png" width="" height="">

Import:
```html
<element name='neuform' src='../../../../../../node_modules/neumorphism/form/form.hml'></element>
```

Usage:
```html
<neuform width="350px" height="300px" border="20px">
    <form onsubmit='onSubmit' onreset='onReset'>
      <neuinput icon="common/icons/user.png" border="30px">
        <input type="email" maxlength="20" placeholder="Email" ></input>
      </neuinput>
      <neuinput icon="" border="20px">
        <input type="password" maxlength="20" placeholder="Password" ></input>
      </neuinput>
      <div>
        <neubutton icon="" width="150px" border="20px">
          <input type='submit' style="border-radius:20px;">Submit</input>
        </neubutton>
        <neubutton icon="" width="150px" border="20px">
          <input type='reset' style="border-radius:20px;">Reset</input>
        </neubutton>
    </div>
  </form>
</neuform>
```

# Input

<img src="sample_images/input.png" width="" height="">

Import:
```html
<element name='neuinput' src='../../../../../../node_modules/neumorphism/input/input.hml'></element>
```

Usage:
```html
<neuinput icon="common/icons/user.png" width="300px" height="50px" border="50px" >
  <input type="text" maxlength="20" placeholder="Input" ></input>
</neuinput>
```

# Label

<img src="sample_images/label.png" width="" height="">

Import:
```html
<element name='neulabel' src='../../../../../../node_modules/neumorphism/label/label.hml'></element>
```

Usage:
```html
<neulabel text="Label" icon="common/icons/heart.png" width="200px" height="50px" border="50px" ></neulabel>
```
