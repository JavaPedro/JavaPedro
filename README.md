Double peso, altura, imc;
    Scanner teclado = new Scanner(System.in);
    System.out.println("Digite seu peso em kg: ");
    peso = teclado.nextDouble();

        System.out.println("Digite sua altura em metros: ");
        altura = teclado.nextDouble();
    imc = peso/(altura*altura);
        if (imc<=18.5) {
          System.out.println("Você está abaixo do peso!");
            }
       else if (imc<=24.9 & imc>=18.5) {
           System.out.println("Você está normal! ");
        }
        else if (imc>=25 & imc<=29.9) {
           System.out.println("Você está com sobrepeso! ");
        }
        else if (imc>=30 & imc<=34.9) {
            System.out.println("Você está obeso! Procure ajuda.");
       }
        else {
            System.out.println("Quadro de risco, obesidade mórbida. Vá a um médico imediatamente!");
       }
