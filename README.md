# Recursividad
La recursividad es una tecnica que tiene como objetivo permitir que las funciones se autoinvoquenpara resolver problemas complejos.

<pre> fun numeroDes(n: Int)
{
    if(n<=0)
    {
      return
    }
    println(n)
}
fun main()
}
   val numero=5
   numeroDes(numero)
}
</pre>

## Llamada recursiva
La funcion se llama asi misma con argumentos que progresan hacia el caso base
<pre>
  numeroDes(n - 1)
</pre>

## Caso Base
La condición que termina la recursion y evita un ciclo infinito
<pre>
  if(n = <=0)
   {
     return
   }
</pre>
