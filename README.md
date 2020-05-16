##Training : Python Y JavaScript
###Respuestas
####Repuesta 1
---

#####JAVASCRIPT

`var lettters = ["a", "b", "c", "d", "e", "f", "g", "h", "i", "j"];
var v1=lettters.indexOf('f'),v2=lettters.indexOf('g'),v3=lettters.indexOf('h')
console.log('Resultado: '+lettters[v1],',',lettters[v2],',',lettters[v3]);´

--#####La solucion sugerida por mi es que a partir de la lista y los elementos para buscar dados.Generar 3 variables cada una con metodo indexOf el cual retorna el primer índice en el que se puede encontrar un elemento dado,  en este caso el elemento seria 'f','g'y 'h'luego con el valor retornado imprimir por consola la ubicacion encontrada de la lista gracias al indexOf.
 
####Repuesta 2
---#####JAVASCRIPT 

`var v1=prompt('Bienvenido Usuario, Ingrese el primer numero.');
 var v2=prompt(' Ingrese el segundo numero.');
 var resultado=v1*v2;
 document.write(v1,' * ',v2,' Resultado : ',resultado);´
 
---#####PYTHON

`v1= int(input("Bienvenido usuario, Ingrese el primer numero: "))
v2= int(input(" Ingrese el segundo numero: "))
resultado=v2 * v1
print(v1,' * ',v2,' Resultado : ',resultado)´
####Repuesta 3

---#####PYTHON
`lista=[]
for x in range(0,5):
valores= float(input("Ingrese valor flotante: "))
lista.append(valores)
print(lista)´

---#####JAVASCRIPT
`var array=[];
for(var i=0, x=5;i<x;i++)
{
    var valores=parseFloat(prompt('Ingrese valor florante: '));
    array.push(valores);
}
console.log(array);´

####Respuesta 4 
`no realizada´
####Respuesta 5
`no realizada´

####Respuesta 6
---#####JAVASCRIPT

`list1 = [12, 15, 32, 42, 55, 75, 122, 132, 150, 180, 200];
multiples5=[];
for (i=0; i<list1.length;i++)
{
    v=list1[i];
    resto = v % 5;
    if(resto==0){
        if(v <150){multiples5.push(v);}
        } 
}
console.log(multiples5);´
---#####PYTHON
`list1 = [12, 15, 32, 42, 55, 75, 122, 132, 150, 180, 200]
multiples5=[]
for i in range(len(list1)):
  v=list1[i]
  resto =v % 5
  if(resto==0):
    if(v <150):
      multiples5.append(v)
print(multiples5)´

####Respuesta 6
---#####se ingresa una lista(python) o un array (caso de javascript)donde se encontrarn los valores 5 4 3 2 1.luego se recorrera esa lista desde el primer valor hasata el ultimo que seria desde 5 hasta 1  y mostraria los valores.despues borraria el primer numero.y repetiría la secuencia hasta que no hayan mas valores


---#####JAVASCRIPT
`
var number=[5,4,3,2,1];
for (var index = 0; index < number.length; index++) {
    document.writeln(number[index]);
} 
number.shift();   
document.write('<br>');
for (var index = 0; index < number.length; index++){   
    document.writeln(number[index]); 
}
number.shift();
document.write('<br>');
for (var index = 0; index < number.length; index++){
    document.writeln(number[index]);
} 
number.shift();
document.write('<br>');
for (var index = 0; index < number.length; index++){
    document.writeln(number[index]); 
}
number.shift();
document.write('<br>');
for (var index = 0; index < number.length; index++){  
    document.writeln(number[index]); 
}´

---#####PYTHON
`
list1=[5,4,3,2,1]
for i in range(len(list1)):
  print(list1[i], end=' ')
list1.pop(0)  
print(' ')
for i in range(len(list1)):
  print(list1[i], end=' ')  
print(' ')
list1.pop(0)  
for i in range(len(list1)):
  print(list1[i], end=' ')
print(' ')
list1.pop(0)  
for i in range(len(list1)):
  print(list1[i], end=' ')
print(' ')
list1.pop(0)    
for i in range(len(list1)):
  print(list1[i], end=' ') ´

####Respuesta 8
---#####el  script esta escrito  en python  por lo tanto en un compilador de java si encontrarias un error. en cambio siempre y cuando se ejecute en un compilador de python no tendria ningun errorya que esta bien escrito en ese lenguaje.para obtener el siguiente resultado hay que hacer esto:
 `for i in range(5):
    print(i)
print('listo!')´
####Respuesta 9
`def dataEstudiante(nombre, edad):
print(nombre, edad)
def mostrarEstudiante(nombre,edad):
    dataEstudiante(nombre,edad)
mostrarEstudiante('victor',36)´

####Respuesta 10
---#####LA Funcion:
`def dataEmpleado(nombre, salario=29000):
    print("Empleado", nombre, "El sueldo es:", salario)´
---#####recibe como parametros nombre y salario. salario tiene como valor default 29000 es decir que si el parametro salario no recibe un valorretoma este valor  automaticamente.por ejemplo si llamo ala funcion asi
`dataEmpleado("Juan", 24000)´---###imprime el nombre juan y el salario 29000 
-otro ejemplo dataEmpleado("Juan") si la funcion se ejecuta de esta manera imprimiria el nombre solo pero como le asignamos el valor default imprime el nombre juan y el salario 29000 
####Respuesta 11
---#####JAVASCRIPT
`function mixstring(str1,str2)
{
     
   c=parseInt(str1.length / 2 ); //MITAD
   c2=parseInt(str2.length / 2 );
   c3=str1.length -1;//ULTIMO
   c4=str2.length -1;
   micadena=[str1[0]+str2[0],str1[c],str2[c2],str1[c3],str2[c4]];//valores juntos
   nc=micadena.join('');//convierto una nueva cadena
   console.log(nc);

  
}
mixstring('Argentina','Uruguay');´
---#####PYTHON
`def mixstring(str1,str2):

     
   c=int(len(str1) / 2 )
   c2=int(len(str2) / 2) 
   c3=int(len(str1) -1)
   c4=int(len(str2) -1)
   micadena=[str1[0],str2[0],str1[c],str2[c2],str1[c3],str2[c4]]
   nc =''.join(micadena)
   print (nc)
  
mixstring('Argentina','Uruguay');´
####Respuesta 12
`miCadena="“acoltrapersobrabilacodaNaNy!";
var unicos = Array.from(new Set(miCadena)).join('');
cant=[];
//buscando ocurrencias
for(var i=0;i<unicos.length;i++)
{ cuenta=0;
    pos=unicos[i];  
    for(var j=0;j<miCadena.length;j++)
    { 
        pos2=miCadena[j];
        if(pos==pos2)
        {
            cuenta++;
        }
    }
    cant.push(cuenta); 
}

//mostrando caracter + cant de ocurrencias

    document.write('Cadena :',miCadena,'<br>');
    for (i=0; i<unicos.length;i++)//listo todos los eelementos
    {
       document.write('Caracter: '+unicos[i]+' = '+cant[i]+' <br>');
    }´

---#####PYTHON
`miCadena="“acoltrapersobrabilacodaNaNy!"
unicos= set(''.join(miCadena))
nc =''.join(unicos)
cant=[]
print(nc)
for i in range(len(nc)):
  cuenta=0
  pos=nc[i]  
  for j in range(len(miCadena)):
    
    pos2=miCadena[j]
    if(pos==pos2):
     cuenta=cuenta+1
    
cant.append(cuenta)
print('Cadena :',miCadena);
for k in range(len(cant)):
  print('Caracter: ',(nc[k]),' = ',(cant[k]),)
  print(' ')´
####Respuesta 12
`no realizada´