# proje4

 Scanner klv = new Scanner(System.in);
        System.out.println("yaricapi giriniz");
        int r = klv.nextInt();
        System.out.println("Daire diliminin acisini giriniz");
        int a = klv.nextInt();
        double Pi = 3.14;
        double formul = (Pi + (r * r) * a) / 360;
        System.out.println("Daire diliminin alanı" + formul);
