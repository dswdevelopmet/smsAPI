# smsAPI
API para envio de mensajes de texto en Puerto Rico.

-	PARA USO DE PRUEBA Y DESARROLLO SOLAMENTE     - 

URL: https://apex.oracle.com/pls/apex/smsapi/api/send? <br>
Método: Get

Importante! <br>
<strong> La consulta no devuelve ningún valor. </strong> <br>
<strong> Un solo número por consulta. </strong>


Variables:<br>
<strong>*num*</strong> ------------------- requerida------------------ número de teléfono del destinatario <br>
<strong>*msg*</strong> ---------------- requerida------------------ mensaje de texto <br>
<strong>*sub*</strong> ----------------- opcional ------------------- encabezado  

Ejemplo:  

num=7871234567&msg=api&sub=test

https://apex.oracle.com/pls/apex/smsapi/api/send?num=7871234567&msg=api&sub=test

-La suma de caracteres del encabezado y del cuerpo del mensaje no deben sobrepasar 60 caracteres <br>
-Los espacios cuentan como un carácter <br>
-Los mensajes llegarán de un número aleatorio desde: noreply@oracle.com <br>
-Los mensajes no se almacenan en cola, la persona debe tener cobertura al momento de ser enviado para que se reciba el mensaje.




https://www.facebook.com/dswdev <br>
developdsw@gmail.com

