# Churn-prediccion

Para cualquier compañía es fundamental identificar clientes con mayor riesgo de fuga o churn. Utilizando datos históricos podemos determinar la probabilidad de que un cliente decida abandonar nuestra compañía. El desafío está en encontrar un modelo que pueda predecir correctamente casos de churn. 
La data disponible corresponde al archivo “Telco-Customer-Churn.csv”, que contiene data histórica de 7.043 clientes con 21 características (columnas). La descripción de estas features es la siguiente: 
-	customerID: identificador del cliente
-	gender: género del cliente (male-hombre/female-mujer)
-	SeniorCitizen: indicador sobre si el cliente es un ciudadano de la tercera edad (1/ 0)
-	Partner: el cliente posee pareja (Yes/No) 
-	Dependents: el cliente posee dependientes (Yes/No) 
-	Tenure: antigüedad del cliente en días 
-	PhoneService: el cliente posee servicio telefónico (Yes/No)
-	MultipleLines: el cliente posee más de una línea telefónica (Yes/No/No phone service)
-	InternetService: proveedor de servicio de internet del cliente (DSL/Fiber optic/No)
-	OnlineSecurity: el cliente posee seguridad online (Yes/No/No internet service)
-	OnlineBackup: el cliente posee copias de seguridad online (Yes/No/No internet service)
-	DeviceProtection: el cliente posee protección para dispositivo (Yes/No/No internet service)
-	TechSupport: el cliente posee soporte técnico (Yes/No/No internet service)
-	StreamingTV: el cliente posee servicio de TV streaming (Yes/No/No internet service)
-	StreamingMovies: eel cliente posee servicio de películas en streaming (Yes/No/No internet service) 
-	Contract: vigencia del contrato con el cliente (month-to-month, one year, two year)
-	PaperlessBilling: el cliente posee facturación electrónica (Yes/No)
-	PaymentMethod: medio de pago (electronic check, mailed check, bank transfer (automatic), credit card (automatic))
-	MonthlyCharges: cantidad cobrada mensualmente al cliente 
-	TotalCharges: cargos totales cobrados al cliente
-	Churn: el cliente ha dejado la compañía en el último mes (Yes/No)

El objetivo del desafío es desarrollar un modelo que pueda predecir si un cliente dejará la compañía
