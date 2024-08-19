Base para resolución de problemas:

`#include <iostream>

    using namespace std;

    void solve() {}

    int main() {
        ios_base::sync_with_stdio(0);
        cin.tie(0);
        int t = 1;
        // cin >> t;

        while (t--) {
            solve();
        }
        return 0;
    }

ATAJOS EN NEOVIM:

### Modo Normal

- **`:q`**: Salir de Neovim.
- **`:w`**: Guardar el archivo actual.
- **`:wq`**: Guardar el archivo actual y salir de Neovim.
- **`u`**: Deshacer la última acción.
- **`Ctrl + r`**: Rehacer la última acción deshecha.
- **`yy`**: Copiar (yank) una línea.
- **`dd`**: Cortar (delete) una línea.
- **`p`**: Pegar después de la posición del cursor.
- **`P`**: Pegar antes de la posición del cursor.
- **`x`**: Borrar el carácter bajo el cursor.
- **`dw`**: Borrar una palabra.
- **`d$`**: Borrar desde el cursor hasta el final de la línea.
- **`gg`**: Ir al inicio del archivo.
- **`G`**: Ir al final del archivo.
- **`0`**: Ir al inicio de la línea actual.
- **`$`**: Ir al final de la línea actual.
- **`/texto`**: Buscar "texto" en el archivo.
- **`n`**: Ir al siguiente resultado de búsqueda.
- **`N`**: Ir al resultado de búsqueda anterior.

### Modo de Inserción

- **`i`**: Entrar en modo de inserción antes del cursor.
- **`I`**: Entrar en modo de inserción al inicio de la línea.
- **`a`**: Entrar en modo de inserción después del cursor.
- **`A`**: Entrar en modo de inserción al final de la línea.
- **`o`**: Insertar una nueva línea debajo y entrar en modo de inserción.
- **`O`**: Insertar una nueva línea encima y entrar en modo de inserción.
- **`Esc`**: Salir del modo de inserción y volver al modo normal.

### Modo Visual

- **`v`**: Entrar en modo visual para seleccionar texto.
- **`V`**: Entrar en modo visual de línea para seleccionar líneas completas.
- **`Ctrl + v`**: Entrar en modo visual en bloque para seleccionar columnas de texto.
- **`y`**: Copiar (yank) el texto seleccionado.
- **`d`**: Cortar (delete) el texto seleccionado.
- **`>`**: Indentar el texto seleccionado.
- **`<`**: Desindentar el texto seleccionado.

### Navegación entre archivos

- **`:e nombre_archivo`**: Abrir un archivo en una nueva ventana.
- **`:bn`**: Ir al siguiente buffer.
- **`:bp`**: Ir al buffer anterior.
- **`:bd`**: Cerrar el buffer actual.
- **`Ctrl + ^`**: Alternar entre los dos últimos buffers abiertos.

### Divisiones y ventanas

- **`:split`** o **`:sp`**: Dividir la ventana horizontalmente.
- **`:vsplit`** o **`:vsp`**: Dividir la ventana verticalmente.
- **`Ctrl + w, h`**: Moverse a la ventana izquierda.
- **`Ctrl + w, l`**: Moverse a la ventana derecha.
- **`Ctrl + w, j`**: Moverse a la ventana de abajo.
- **`Ctrl + w, k`**: Moverse a la ventana de arriba.
- **`:q`**: Cerrar la ventana actual.

INPUT (Entrada de datos):

` int a, b;`
`string x;
`cin >> a >> b >> x;`

TIPOS DE DATOS:

- Numéricos:
	- Enteros:
			- int (4 bytes) - Cada byte tiene 8 bits. (32 BITS EN TOTAL).
				Valor como mínimo:  -2^31
				Valor como máximo: 2^31 - 1
			- long long:
				Valor como mínimo:  -2^63
				Valor como máximo: 2^63 - 1

	- Flotantes:
			- float (Parte entera: 2 bytes, Parte decimal: 2 bytes)-
			- double
			- long double
	- 

