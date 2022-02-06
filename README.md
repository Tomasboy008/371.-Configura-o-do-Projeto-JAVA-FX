# 371.-Configura-o-do-Projeto-JAVA-FX
Comecando aula de JAVA FX
INICIO
_________________________________
module exerciciosfx {
	requires javafx.controls;
	opens basico;
}
_________________________________

INICIO
_________________________________

package basico;

import javafx.application.Application;
import javafx.stage.Stage;

public class PrimeiroFX extends Application {

	@Override
	public void start(Stage primaryStage) throws Exception {
		
		primaryStage.show();
	}
	public static void main(String[] args) {
		launch(args);
	}
}
