# Avengers

El cuartel general de los Avengers para aprender Git y GitHub

Toda la información aquí utilizada sale de Wikipedia y Marvel.com

    **Pruebas lambdas, Stream**
    List<Integer> lista = Arrays.asList(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);

    lista.sort((n1, n2) -> (n1.compareTo(n2)));

    for (Integer integer : lista) {
      System.out.println(integer);
    }
    
    lista.forEach((n1) -> System.out.println(n1));
    
    lista
      .stream()
      .filter((n) -> n >= 5)
      .mapToInt(v -> v.intValue())
      .forEach((n) -> System.out.println(n));


    Pruebas varargs
    
    //Definición del método
      static void vaTest(int ... v) {        // o en el caso de las facturas: vaTest (Factura ... v)
    System.out.println("Número de args: " + v.length);
    System.out.println("Contiene: ");

    for (int i = 0; i < v.length; i++) {
      System.out.println(" arg " + i + ": " + v[i]); 
    }
    System.out.println();
  }
  // LLamada (ejemplo) al método
  
    vaTest(10, 10);                          // o en el caso de las facturas: vaTest (factura1, factura2, factura3)
    
    
