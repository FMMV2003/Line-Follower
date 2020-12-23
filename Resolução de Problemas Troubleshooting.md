Os únicos problemas que nós tivémos foram com as bibliotecas dos sensores e do motor shield e os valores de KD e KP.


A biblioteca do Motor Shield que tem de ser instalada é a Motor Shield V1 Library e depois de adicionar no código, deverá mostrar a seguinte mensagem "#include <AFMotor.h>
". Para os sensores teremos de instalar a versão 3.0.0 e após adicionar a biblioteca irá aparecer "#include <QTRSensors.h>".


Os valores da PID, terão de ser ajustadas à pista, é importante perceber o que cada variável controla.


The only problems we faced were the libraries we need to install as well the values of KD and KP.


The motor shield librar that needs to be instaled is Motor Shield V1 Library, and after incluiding it in the code it will appear this "#include <AFMotor.h>". For the sensors we 
have to install the 3.0.0 version of the QTR Sensors and after adding it to the code you will see this message "#include <QTRSensors.h>".

The values we used on the PID controller, have to be adjusted to your car, and track dimensions, you must understand what KD and KP stand for.
