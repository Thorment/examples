# examples
https://github.com/TazztheMonster/ExampleFunctions/tree/master/src

// Switch Case  ///////////////////////////////////////////////

String lichtschalter = "an";
switch (lichtschalter) {
    case "an":
        System.out.println("Das Licht ist an");
	  break;
    case "aus":
        System.out.println("Das Licht ist aus");
        break;
    default:
        System.out.println("geht nicht");
}

// File Reader  /////////////////////////////////////////////////

FileWriter output = new FileWriter("data/data.bin");

try(BufferedWriter bufferedWriter =
    new BufferedWriter(output)){

    bufferedWriter.write("Hello World");

}

