![](https://upload.wikimedia.org/wikipedia/commons/3/3a/Logo_ESPEOk.png)


#  LABORATORIO 7
                                                                            
                                                                            
                                                                            
                                                                            
                                                                            
                                                                            
                                                                           
                                                                           
       Janeth Katherine Oyasa Sepa, Juan Daniel Tixi Yupa
       DEPARTAMENTO DE ELECTRICA Y ELECTRONICA
       ESPE, Autopista General Rumiñahui S/N y Ambato, Sangolquí 171103.
       E-mail: jkoyasa@espe.edu.ec, jdtixi@espe.edu.ec
       Noviembre 2020 – Abril 2021
       Fundamentos de Circuitos Eléctricos
       








# 4.Lista de componentes

A continuación, se presenta ña lista de componentes para el presente laboratorio

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161290219_268113908087986_3494898432595147568_n.jpg?_nc_cat=111&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFb-xLtWDypR8Idwo9o5FLGjoWbI0Y8F-2OhZsjRjwX7bh9hDiMo_CUt2ztcGHK-9fPYdHy9XI8ImhsnAW64v12&_nc_ohc=GWXfvLOz-o0AX89WeO0&_nc_ht=scontent.fuio1-1.fna&oh=a649a32dcdfcc6e40ef76674488ce076&oe=607563ED)

5.Explicación

Primero que todo debemos armar el circuito que se muestra a continuación.

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/162133115_268113914754652_6266679834339938876_n.jpg?_nc_cat=111&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeGG7eMxm3AG7WMSDUtYm6BgorlrJsORFtmiuWsmw5EW2ay1NvydilydP8SelFhYFjIa6dZcPdQLfVWm-I6Rk2v5&_nc_ohc=ZGiek1NFEyYAX80PpWw&_nc_ht=scontent.fuio1-1.fna&oh=8a3e9162c330ab99209e7e0becfdc33a&oe=6076C2D9)

Conectamos la fuente de 12 V a la resistencia de 560 Ohm, luego, de la segunda terminal de la resistencia conectamos la primera terminal de la resistencia de 4.7 k Ohm y  la conectamos además al polo negativo de la fuente de 2 V, después de esto procedemos a conectar al polo positivo de la fuente de tensión de dos voltios a cada una de las terminales de las resistencias de 100 Ohm y 330 Ohm, para conectar ahora la segunda terminal de la resistencia de 100 Ohm a la primera terminal del resistor de 1k Ohm, por ultimo empatamos todos los terminales sueltos a la polaridad negativa de la fuente de 12 V.

En esta práctica nos estamos enfocando a lo que es Voltaje y Resistencia de Thévenin, por lo que primero calcularemos a mano el circuito equivalente, para luego pasar a la practica en el laboratorio virtual.

Entonces hallaremos primero la resistencia de Thévenin, para esto, según el teorema, procedemos a apagar todas las fuentes, tanto las de tensión como las de corriente.

En nuestro circuito tenemos dos fuentes de voltaje, y por lo tanto estas se van a transformar en cortocircuitos al momento de apagarlas, y a más de esto debemos retirar nuestra resistencia de carga, teniendo lo siguiente.

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161638488_268113921421318_1060297456484941083_o.jpg?_nc_cat=107&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFRE_aDc0c_WIjJkBotzsTlMztduHwEh04zO124fASHTqIt94cBDXQlq6fss5UGv2T7SxyNhBsQgiXsjDJAPveC&_nc_ohc=SqB6Jvngs2IAX8f1J6a&_nc_ht=scontent.fuio1-1.fna&oh=9c003d3e8e54eebdfa62f5a6eb5664ca&oe=607560F6)

Hallamos la resistencia vista desde los terminales a y b.

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161205426_268113954754648_6463816943439064176_n.jpg?_nc_cat=100&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeH7Or_HHe1mLNtpoXHsvSU8v011-cot8zy_TXX5yi3zPNXNWoEHCbYxMyznwSBOj191HSJEcqRoSBeG32nZC4Jq&_nc_ohc=Cfx4jI8_IUUAX8G3Rcn&_nc_ht=scontent.fuio1-1.fna&oh=a10def29baf3072ce18fb98f9cebe2de&oe=6077D0EE)

Por ultimo sumamos el paralelo equivalente a la de 100 Ohm, que nos queda
R_TH=298.86
El cuál es la resistencia de Thévenin

El siguiente paso es hallar el voltaje de Thévenin, para esto desconectamos nuestra resistencia de carga, que es la R5, y en este caso usaremos el análisis de mallas en el siguiente circuito para determinar el voltaje en las terminales a y b.

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161511889_268113974754646_4492846862338723985_o.jpg?_nc_cat=108&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeE0AD3gJVfkGSbHNxTu0hQLsdAtVCMgy6-x0C1UIyDLr4ZDKyTcKI_626O_F9ESWUqPZXtIuPp2aUpmOosF3rvF&_nc_ohc=-QLo8HPzJfEAX-7XUgy&_nc_oc=AQkG0S3WEUpyKzGHDu8qbVSxCMOvWTPQodK2wVy-ILizA7BR4a3xJjeWgKTEhdIJS2M&_nc_ht=scontent.fuio1-1.fna&oh=18a646f40823fea22e762729a87534b9&oe=6075F186)


![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161274519_268113964754647_4219248349811034242_n.jpg?_nc_cat=104&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFFwmuY4xBm7nGK1PWWwgLIP5UdeukIRWw_lR166QhFbNpgSP6znZUbVLLmlg3_HSojWVtv_J4cv7qy2BApz-hf&_nc_ohc=VkQX1HVT8poAX8U03Gt&_nc_ht=scontent.fuio1-1.fna&oh=b3d90ea77e582f00cc41cecdaa682780&oe=6076E553)

Como matriz tenemos:
![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161419785_268114194754624_4979582585700036982_o.jpg?_nc_cat=105&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeF7DhdE5JExuB_uv7CShcbkF-h_wNl_jUIX6H_A2X-NQmyWDYk0s3yRIITDF7_QiKYBzPORe9Af5UtopFlixFZo&_nc_ohc=1brrHafrnl4AX9dre3b&_nc_ht=scontent.fuio1-1.fna&oh=806e334c34b8b34ee46b451b6eee5c60&oe=6075240A)

Que al resolverla no da como resultado:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161742788_268114008087976_890477559932154957_n.jpg?_nc_cat=102&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeGRAa1U0XEdJru4oaIvhdnXJUtQQTm38solS1BBObfyyn0MLdabXy5xBNvfNu_Nck8c23nKwW1vVLhU9y2rj5KL&_nc_ohc=tTc112ZrECsAX_pddyD&_nc_ht=scontent.fuio1-1.fna&oh=043c1e4c3ca7f93314d474d949100bd7&oe=607558E3)

Y para hallar el voltaje de Thévenin simplemente debemos multiplicar la resistencia de 330 con la segunda corriente, ya que ese es el voltaje visto desde las terminales a y b, nos queda:

V_th=5.0556

Implementado nos queda:


![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161888919_268114024754641_3873315583095111240_o.jpg?_nc_cat=102&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeGdzUSWPpt3p_qe4dPCdfZp2aXg7lzn1y7ZpeDuXOfXLtE09zjM-Y9B8-0tYUVoo368uG21Q6MVIrhV3QBejpr3&_nc_ohc=d61Mnc3_CNcAX8mGOil&_nc_ht=scontent.fuio1-1.fna&oh=78556c5e9a6466c2bdf259f26b7cd70e&oe=6077AB13)


![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161056876_268114031421307_5281515620438977216_n.jpg?_nc_cat=109&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeHVjfaG7lxlluWcfdUaWzmnjbVJqC2KTuKNtUmoLYpO4ilutMpZ__PM01XCppJI5mz-9o4hlGcVvC3G_ByhIuoL&_nc_ohc=iFOAOMzX0yoAX_cF4Dw&_nc_ht=scontent.fuio1-1.fna&oh=ddae0bcb347f66578bb5cfde936b827b&oe=60782F4F)

Comprobémoslo ahora, realizando el análisis de mallas el circuito inicial, fijando las corrientes tenemos:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161290219_268114068087970_8121641739662009690_o.jpg?_nc_cat=103&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeHewbLyaWH-Z72rUbu3ZAF0Y3DmCN1suRxjcOYI3Wy5HEOLF-o2-bR2B8oKQlR9zVmXgZrEy_PJAhwSWZbygBep&_nc_ohc=hS6jdoFlhNMAX9TT7ew&_nc_ht=scontent.fuio1-1.fna&oh=945bad1d78905eca00de34cc1d40fbd8&oe=60786970)

Las ecuaciones de las mallas quedan de la siguiente manera:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/162112586_268114061421304_3272143376453405822_n.jpg?_nc_cat=110&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeHei7bPanlpRPiaknv6-RvE0Bvs8YC3F5jQG-zxgLcXmPwkOw3m9mjlD5bgLjPPSNZSAVX0DaWouMQrWE2-NzaP&_nc_ohc=FOzE7skvdhUAX8_F0lP&_nc_ht=scontent.fuio1-1.fna&oh=7d661a23fa65e6cc043263680f7295be&oe=60787A0A)

Sistema de ecuaciones que podemos resolver usando matrices o directamente en calculadora:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161838129_268114094754634_3365924948574180318_o.jpg?_nc_cat=104&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeG0xjJnW4UCvZcjyq2N4b6Cc9-Ih5lDwBBz34iHmUPAEKwWd1LKUnSAHQjU3ULga0kiHzDOWkHf5Us9U6mGQ27U&_nc_ohc=besQHtBKylIAX8g4L6l&_nc_ht=scontent.fuio1-1.fna&oh=0e6bd0e41435984013892c858c488190&oe=60752223)

Así tenemos los siguientes resultados:

i_1=0.017 A
i_2=0.0168
i_3=0.003892=3.892 mA

La ultima corriente la i_3 es la corriente que pasa por la resistencia de carga y es la corriente que encontramos realizando el equivalente de Thévenin, por último el voltaje:

V_R5=3.892m*1000=3.892 V

Con lo que queda demostrado el teorema de Thévenin.

Pasamos ahora a realizar las mediciones en el circuito armado en el laboratorio:

Medimos el voltaje la corriente de la resistencia 5 de 1k Ohm en el circuito normal:

i_R5=3.89 V
V_R5=3.89 mA


Midiendo el voltaje de Thévenin con la R5 desconectada tenemos:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/162026789_268114108087966_1169851217029847150_o.jpg?_nc_cat=102&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeG43RH19TV3zXUrwHD9WBlEtlSVu5k8Nqi2VJW7mTw2qFE7xvAMh2cw4KkaKs2gy24Y3gFd0zQoysb5GRRWSSlU&_nc_ohc=R17p1h4rsk4AX9zY0uI&_nc_ht=scontent.fuio1-1.fna&oh=d2bb1a9978de3d4c0f9e576369d0a968&oe=6076E274)

Anulando los voltajes en el circuito tenemos:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/160871828_268114111421299_5728167846727932638_o.jpg?_nc_cat=107&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFZKUKIT3mDcQe9HsQkYC8tcfwsLSZ9TIxx_CwtJn1MjFhptbLM2T-8ZpaIMjt_8w1gOo5RtUWs8Vymsqjh21c4&_nc_ohc=eOOeaUiQlJcAX8B4lzE&_nc_ht=scontent.fuio1-1.fna&oh=5ce32fd05dba19c9803ae0fac55523ac&oe=60786938)

Que es la resistencia de Thévenin

Implementemos el Equivalente de Thévenin calculado anteriormente en el simulador, nos queda así:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161606853_268114141421296_1666430086027579776_n.jpg?_nc_cat=107&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeHs2ajkO3ZS8F685T1zSXMAdDmQPkmJTaR0OZA-SYlNpBRtJW-oWtbmtkdacHNe15wEAtTQ6PHbX3ZoB1dUtfSU&_nc_ohc=t1XaIWpepy0AX8gQg_P&_nc_ht=scontent.fuio1-1.fna&oh=9d96b6695599028dd610094ff1315b56&oe=60775A8D)

Midiendo la corriente de R5 

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161179297_268114158087961_6000468345435537779_o.jpg?_nc_cat=100&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeGQE6dA3LSwzRadSwYTPqR-Nyf-FbRQMKo3J_4VtFAwqvfa2InAttYNgMAy2YN0tOcOLH-qNFAV6WdMQmFYiSC-&_nc_ohc=FNLrOSfu3r8AX9b_6Bh&_nc_ht=scontent.fuio1-1.fna&oh=a20ca31ee653eca2b312ea84d2af96aa&oe=6075627B)

Y el voltaje

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161557837_268114168087960_6342389199590692290_o.jpg?_nc_cat=100&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeGIWNA_3ysTAtLkGISzDJI5klkb4Om7naKSWRvg6budon2ZHTqo8DMlZmE9FBm22Kz3qcqxgWYoEho9t48pmjlM&_nc_ohc=p87FvYnZMuYAX8JnE9s&_nc_ht=scontent.fuio1-1.fna&oh=7714437a20a83ed296a466365d176f8b&oe=6076F57B)

Anotemos todos los resultados obtenidos en una tabla resumen, con la que podamos comparar los datos, así tenemos:

Tabla 1 de resultados

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161269806_268114188087958_5866709896566754092_n.jpg?_nc_cat=105&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeE3ruJJf6uIVCOXAY--dl-GmiNZwd8mZe6aI1nB3yZl7hushVKx7Cgwd5C1KRiEDQjejbM2W41GlflaZQ2rOSgK&_nc_ohc=OHaYb7cYGVAAX-SX81J&_nc_ht=scontent.fuio1-1.fna&oh=f337cc44c4fc6368b9edaceb76d17037&oe=607570ED)
Necesitamos el error:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161186961_268114208087956_1633560894274627341_n.jpg?_nc_cat=104&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeHSasYVPgB_zywg7udFYeDYcAMMogxj8ClwAwyiDGPwKcT7PUFtCQwbyq6Dt1u7wQ6bfvg3neeDLAShJN81Y3Kb&_nc_ohc=qH1g8XEWWoMAX_J7m8A&_nc_ht=scontent.fuio1-1.fna&oh=487c9af7a7af6b8ed49ae3a4083d1668&oe=6078F760)

Y para el voltaje y resistencia de Thévenin 

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161076032_268114214754622_8439870182450936278_n.jpg?_nc_cat=106&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFAWWH4-TEFSGKZAhtkQZBfgvao136-AZeC9qjXfr4Bl9qGJDfsIeog2bPj6U4G_W5dWli4iZFQTphAyYF016gU&_nc_ohc=BUCfmrCG7gwAX90Un9a&_nc_ht=scontent.fuio1-1.fna&oh=234dee692b4e852ceadc64f56c8ca753&oe=6075593A)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/162537069_268114244754619_2849763629495763141_n.jpg?_nc_cat=101&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeH4guCDkNfCzjb8P1dIUzhwpmCcWLlOwFamYJxYuU7AVu9BBOFvoECIIZZfmiAafVNneM1Y1Xki-Vcz1akLzR44&_nc_ohc=rae9O7ovWqEAX-akU22&_nc_ht=scontent.fuio1-1.fna&oh=34ee1132dae4d94ad6a019c9da9fb0f8&oe=6078716D)

# 6.Descripcion de prerrequisitos y configuración

Como prerrequisito tenemos que tener en cuenta nuestros conocimientos acerca de las leyes de Ohm y Kirchhoff, leyes que siempre estarán presente a lo largo de la práctica, además de tener presente de conceptos teóricos como el voltaje y corriente de Thévenin.

Para la implementación exitosa del circuito, se debe colocar correnctamente los valores de las resistencias en cada unod de los resistores, caso contrario llegaríamos a resultados incoherentes e irreales, en cada fuente de voltaje debemos ajustar correctamente el valor, y conectarlos tal cual esta en el circuito indicado.

Para la realización de las medidas con el multímetro debemos tener en cuenta aspectos que ya sabemos como la medida de correinte en serie y la medida del voltaje en paralelo, ajustando el multímetro en amperaje y voltaje según sea el caso.

# 7.Aportaciones o Recomendaciones

•	Ser cuidaosos en la colocación de los valores en los resistores, unque esta tarea resulta bastantemente fácil, si nos descuidamos al final ponemos valores que no son y tenemos que realizar los cálculos respectivos de nuevo.

•	Apagar todas y cada una de las fuentes para hallar la respectiva resistencia de Thévenin con el multímetro, caso contrario porvocariamos un daño en el multímetro al momento de realizar las mediciones.

•	Usar la mayor cantidad de decimales como nos sea posible a fin de tener una mayor precisión en los resultados

# 8.Concluiones

•	Finalmente comprobamos que el teorema aprendido en la teoría es correcto y se cumple en este caso con un circuito ya ensamblado en la realidad, asi que si queremos analizar un circuito tremendamente grande y extenso en solo dos termianles, podemos apoyarnos en el teorema, y no evitamos realizar los cálculos cada vez que los cálculos cada vez que colocamos una nueva resistencia en las terminales que estamos analizando.

# 10Bibliografia

# 11Anexos


![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161675454_268123821420328_4409475958721936390_o.jpg?_nc_cat=109&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeHQ1RO5YF47ni6WN08teJq1XfZRvwmeyCJd9lG_CZ7IInOuxjT7ecUP04W5R2FKaq13XXL2QYeMobcKfDFOZBxA&_nc_ohc=NkBPJ8F4RRIAX-dLpQC&_nc_ht=scontent.fuio1-1.fna&oh=af473fde87ec51169ebeee94978e215b&oe=6078E464)
![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161431969_268123808086996_7622892132928758170_o.jpg?_nc_cat=100&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeGzn2QJyt7CVJo0OWOxfjfMQPllujlmL2lA-WW6OWYvaWVTeOjJFU23EGRnaB44ATxqBX3wK1wv4xXz9ZQ66Upl&_nc_ohc=Lks4c_mFx7IAX9TD4mh&_nc_ht=scontent.fuio1-1.fna&oh=d71a995eab1ef2a5917027b2526d0816&oe=60776396)
![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/161204122_268123814753662_7649084519829256592_o.jpg?_nc_cat=105&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeE7chuHhRTMPOBA8WKqHkuJImZCYA3Eu3UiZkJgDcS7dbFwHA7J9WCxUqn1cgP_du5ddDQ2Q-x2f7ep_KJkcHng&_nc_ohc=5sfc3I1nmq0AX9NvNvV&_nc_ht=scontent.fuio1-1.fna&oh=617d2f03f5f711fa0c7f892cc1796a62&oe=6075E30C)

