# Actividad 6. Analizador Semántico

Esta actividad consistirá en realizar el analizador semántico con lo que se había hecho en la actividad anterior (tanto analizador léxico como sintáctico). También en esta actividad se mostrará tanto los errores semánticos como el propio árbol sintáctico formado por dicho análisis.

Recordando, la gramática utilizada es la siguiente:

[compilador.xlsx](https://github.com/Erosval2101/Traductores_de_Lenguaje_II/files/5646517/compilador.xlsx)

### Código 1:
 
```sh
int main(){
float a;
int b;
int c;
c = a+b;
c = suma(8,9);
}
```

### Código 2:

```sh
int a;
int suma(int a, int b){
	return a+b;
}

int main(){
float a;
int b;
int c;
c = a+b;
c = suma(8.5,9.9);
}
```

## Resultados.

![Ejecucion1](https://user-images.githubusercontent.com/70926870/101234942-8aadd680-3689-11eb-834e-8ee2a4c2dbdb.PNG)

![Ejecucion8](https://user-images.githubusercontent.com/70926870/101234941-8a154000-3689-11eb-9681-951e5c521c83.PNG)
