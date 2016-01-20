Material Tabs
=============
Material Tabs es un componente basado en las lineas de diseño de https://design.google.com/. 

##Defaults
El número de pestañas por defecto es 4 y el rango de pestañas va desde 2 hasta 8.
Para cambiar éstos números el archivo **main.scss** contiene los datos necesarios para recompilarse.

###Ejemplo 1

![alt text](http://s27.postimg.org/5dgcjf4er/Screenshot_2016_01_20_11_36_35.png"Logo Title Text 1")


```html
<!-- DEFAULT: data-tabs-number="4" -->
<div class="material-tabs" data-tabs-number="4">
    <div class="tab-wrap">
        <input type="radio" name="tabs" id="tab1" checked>
        <div class="tab-label-content" id="tab1-content">
            <label for="tab1">Tab 1</label>
            <span class="tab-content for-tab-1">
                <!-- TODO: Content -->
            </span>
        </div>
        <input type="radio" name="tabs" id="tab2">
        <div class="tab-label-content" id="tab2-content">
            <label for="tab2">Tab 2</label>
            <span class="tab-content for-tab-2">
                <!-- TODO: Content -->  
        </div>
        <input type="radio" name="tabs" id="tab3">
        <div class="tab-label-content" id="tab3-content">
            <label for="tab3">Tab 3</label>
            <span class="tab-content for-tab-3">
                <!-- TODO: Content -->
            </span>
        </div>
        <input type="radio" name="tabs" id="tab4">
        <div class="tab-label-content" id="tab4-content">
            <label for="tab4">Tab 3</label>
            <span class="tab-content for-tab-4">
                <!-- TODO: Content -->
            </span>
        </div>
        <div class="slide"></div>
    </div>
</div>
```