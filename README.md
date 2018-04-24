# onoma

Aspect-oriented APL-inspired Programming Language

"onoma" means "name" in greek. Every line in an Onoma program has a name, and each line is allowed only a single operation.

    !:
      a: _ i
      r: a \*

    !!:
      << !
      a+1: a + 1
      
    main:
      a: 4 !
      b: 4 !!
      io: a b stdout
      
When we run the program.

     > onoma factorial-example.onoma
     24
     120
     
