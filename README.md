Ejercicio original


var feature = 'closures';   
(function () {   
    
    if ( typeof feature === 'undefined' ){         
        var feature = 'callbacks';         
        console.log('JS coders love its ' + feature );     
    } else {         
        console.log('JS developers love its ' + feature );     
    }
})();



1.- La variable "feature" por mas que sea una variable global, 
al estar declarada dentro de la funcion anonima, por medio del hoisting se desdobla
y se declara undefined al inicio de la funcion y cuando es evaluada se entra 
a callbacks por aun no estar asignada

