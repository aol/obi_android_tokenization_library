Add CardEncryptionLib.jar file into libs folder of your Android project.
Right click --> Add as Library

Use the following code to encrypt and tokenize a credit card number and cvv.
 
String encryptedCardToken = EncryptCard.encryptCard(cardNumber, cardCvv, domain);

Parameter domain shows the environment of the library usage and can be "DEV" or "PROD" or "QA".
Any other value of domain will be considered as "QA".
