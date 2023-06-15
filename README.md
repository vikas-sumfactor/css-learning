# css-learning

* CSS SELECTOR

    
    ![img_selector](https://github.com/vikas-sumfactor/css-learning/assets/130432414/a4ad7bf7-873b-4597-810b-22f7a12893af)
    
   
   ![Screenshot (177)](https://github.com/vikas-sumfactor/css-learning/assets/130432414/2ce6553f-2fa8-4fc9-bd8a-5ee20d2ec16e)
   
   
  #  Priority Order Of CSS:
    
    
     * inline > internal >external
     
     
   # Comments in CSS:
     
     
     /* This is a single-line comment */
     
     
     
   # RGB Value:
    
     
   In CSS, a color can be specified as an RGB value, using this formula:
   

    rgb(red, green, blue)
    

    Each parameter (red, green, and blue) defines the intensity of the color between 0 and 255.
    

    For example, rgb(255, 0, 0) is displayed as red, because red is set to its highest value (255) and the others are set to 0.
    

    To display black, set all color parameters to 0, like this: rgb(0, 0, 0).
    

    To display white, set all color parameters to 255, like this: rgb(255, 255, 255).
    
    
   # RGBA Value:
   
    RGBA color values are an extension of RGB color values with an alpha channel - which specifies the opacity for a color.

    An RGBA color value is specified with:

    rgba(red, green, blue, alpha)

    The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all)
    
    # HEX Value
    
    In CSS, a color can be specified using a hexadecimal value in the form:

     #rrggbb

    Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).

    For example, #ff0000 is displayed as red, because red is set to its highest value (ff) and the others are set to the lowest value (00).

    To display black, set all values to 00, like this: #000000.

    To display white, set all values to ff, like this: #ffffff.
    
    
   # 3 Digit HEX Value
   
    Sometimes you will see a 3-digit hex code in the CSS source.

    The 3-digit hex code is a shorthand for some 6-digit hex codes.

   The 3-digit hex code has the following form:

   #rgb

   Where r, g, and b represent the red, green, and blue components with values between 0 and f.

   The 3-digit hex code can only be used when both the values (RR, GG, and BB) are the same for each component. So, if we have #ff00cc, it can be written like this: #f0c.
   
   # HSL Value
   
     In CSS, a color can be specified using hue, saturation, and lightness (HSL) in the form:

    hsl(hue, saturation, lightness)

    Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.

   Saturation is a percentage value. 0% means a shade of gray, and 100% is the full color.

   Lightness is also a percentage. 0% is black, 50% is neither light or dark, 100% is white
   
   
   
   # CSS Border Style
    The border-style property specifies what kind of border to display.

    The following values are allowed:

    dotted - Defines a dotted border
    
    dashed - Defines a dashed border
    
    solid - Defines a solid border
    
    double - Defines a double border
    
    groove - Defines a 3D grooved border. The effect depends on the border-color value
    
    ridge - Defines a 3D ridged border. The effect depends on the border-color value
    
    inset - Defines a 3D inset border. The effect depends on the border-color value
    
    outset - Defines a 3D outset border. The effect depends on the border-color value
    
    none - Defines no border
    
    hidden - Defines a hidden border
    
    The border-style property can have from one to four values (for the top border, right border, bottom border, and the left border).
  
