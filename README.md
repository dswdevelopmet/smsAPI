# smsAPI
API para envio de mensajes de texto en Puerto Rico.

-	PARA USO DE PRUEBA Y DESARROLLO SOLAMENTE     - 

URL: https://apex.oracle.com/pls/apex/smsapi/api/send?
Método: Get

Variables:
*num* ------------------- requerida------------------ número de teléfono del destinatario/
*msg* ---------------- requerida------------------ mensaje de texto /
*sub* ----------------- opcional ------------------- encabezado/

Ejemplo:  

num=7871234567&msg=api&sub=test

https://apex.oracle.com/pls/apex/smsapi/api/send?num=7871234567&msg=api&sub=test

-La suma de caracteres del encabezado y del cuerpo del mensaje no deben sobrepasar 60 caracteres
-Los espacios cuentan como un carácter
-Los mensajes llegarán de un numero aleatorio desde: noreply@oracle.com


developdsw@gmail.com

