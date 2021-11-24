# Avengers

El cuartel general de los Avengers para aprender Git y GitHub

Toda la información aquí utilizada sale de Wikipedia y Marvel.com

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
