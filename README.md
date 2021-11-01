# examples


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
// FIle Reader ////////////////////////////
blablaa


// Action Event Handler  ///////////////////////
		centerBtn.setOnAction(new EventHandler<ActionEvent>() {

			@Override
			public void handle(ActionEvent event) {
				System.out.println("jetzt passiert etwas");
				primaryStage.setScene(scene2);
			}
		});
	
	
	
