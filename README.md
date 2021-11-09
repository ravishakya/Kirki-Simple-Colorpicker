# Kirki Simple Colorpicker

**Author      :** Ravi Shakya  
**Author URI  :** https://bizbergthemes.com  
**License     :** GNU General Public License v2 or later  
**License URI :** http://www.gnu.org/licenses/gpl-2.0.html  
**Version     :** 0.2

## Description ##

Simple colorpicker wrapped in modal

![image](https://user-images.githubusercontent.com/11089018/139245474-7ecf0208-7a20-46e9-a97e-81aff81c9149.png)

## Example Code ##

````php
Kirki::add_field( 'bizberg', array(
    'type'        => 'simple-color',
    'label'       => 'Body Background',
    'section'     => 'detail_page',
    'settings'    => 'body_background_gradient1111',
    'description' => 'Simple Color Selector',
    'default'     => 'rgba(30,115,190,0.51)',
    'choices'     => [
        'alpha' => true,
    ],
    'transport' => 'auto',
    'output' => array(
        array(
            'element'  => 'body',
            'property' => 'background',
        ),
    ),
) );
````
**Parameters**

**default** - (string) (optional) Eg : `#000`

**alpha** - (boolean) (optional) // If true, you can control the opacity of the color

## Note ##
You will need to install the kirki plugin first https://wordpress.org/plugins/kirki/

## Changelog ##

= 0.2 =
- Check function before initializing it

= 0.1 =
- Initial Release
