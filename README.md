# klipperizado



                MATERIALES NECESARIOS:
x1 PLACA CONTROLADORA IMPRESORA 3D QUE ADMITA KLIPPER (AQUI HE USADO RAMPS) - https://es.aliexpress.com/item/1005007465107013.html?spm=a2g0o.productlist.main.11.782ciWoyiWoyw7&algo_pvid=78222b89-8782-447f-a3a2-7cfa7c4ac605&algo_exp_id=78222b89-8782-447f-a3a2-7cfa7c4ac605-5&pdp_ext_f=%7B%22order%22%3A%2252%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%2120.90%2118.39%21%21%2121.41%2118.84%21%40210390c917402993333382159e6288%2112000042919868304%21sea%21ES%21859809002%21X&curPageLogUid=psfUn3yt3RhV&utparam-url=scene%3Asearch%7Cquery_from%3A

x4 MOTORES NEMA 17 - https://es.aliexpress.com/item/1005005281739306.html?spm=a2g0o.productlist.main.1.d63d2d4aTTNZ60&algo_pvid=b276e398-8596-414c-8db3-8e654c68662e&algo_exp_id=b276e398-8596-414c-8db3-8e654c68662e-0&pdp_ext_f=%7B%22order%22%3A%22889%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%217.09%217.09%21%21%2152.68%2152.68%21%402103956a17402995527205066eac9e%2112000040072246972%21sea%21ES%21859809002%21X&curPageLogUid=1sYsbJTYPM1q&utparam-url=scene%3Asearch%7Cquery_from%3A

x1 FUENTE DE ALIMENTACION 12V 3A - https://es.aliexpress.com/item/4000521124523.html?spm=a2g0o.productlist.main.5.3b704dbfKBc7ga&algo_pvid=57ae2390-b58a-4c19-91c1-39ae34f753d8&algo_exp_id=57ae2390-b58a-4c19-91c1-39ae34f753d8-2&pdp_ext_f=%7B%22order%22%3A%228815%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%213.89%213.89%21%21%213.98%213.98%21%402103890117402997394393958e5125%2110000002659372397%21sea%21ES%21859809002%21X&curPageLogUid=QoWJLxlMkBCg&utparam-url=scene%3Asearch%7Cquery_from%3A

x4 KIT EXTRUSOR MK8 - https://es.aliexpress.com/item/1005004923874649.html?spm=a2g0o.productlist.main.11.1001No0BNo0B7n&algo_pvid=e176a8ed-a1a1-486a-af55-a8d43d68fd73&algo_exp_id=e176a8ed-a1a1-486a-af55-a8d43d68fd73-5&pdp_ext_f=%7B%22order%22%3A%22537%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%214.03%213.79%21%21%214.13%213.88%21%40211b61ae17402996038501937ea5a8%2112000034678897920%21sea%21ES%21859809002%21X&curPageLogUid=XksYLTKe8sr8&utparam-url=scene%3Asearch%7Cquery_from%3A

x1 VIA 4 A 1 GUIA DE FILAMENTO - https://es.aliexpress.com/item/1005007494013265.html?aem_p4p_detail=2025022300363310528218103721850008669381&algo_pvid=10b00fd2-d812-4d84-9450-50396ba177cb&algo_exp_id=10b00fd2-d812-4d84-9450-50396ba177cb-7&pdp_ext_f=%7B%22order%22%3A%22540%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%218.36%217.69%21%21%2162.11%2157.13%21%402103894417402997938763047ec6d3%2112000041015053166%21sea%21ES%21859809002%21X&curPageLogUid=RGj1Adnaw4vD&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=2025022300363310528218103721850008669381_2

https://www.printables.com/model/616979-4-to-1-bowdenptfe-tube-joinersplitter-straight-top

https://www.printables.com/model/488193-4-to-1-bowdenptfe-tube-joinersplitter-stronger-bas

3 METROS TUBO PTFE - https://www.amazon.es/dp/B07MBGQYT9?ref=ppx_yo2ov_dt_b_fed_asin_title

x4 CONECTORES PC4-M6 -

x5 CONECTORES PC4-M10 -

x1 MG90s - 


       *OPCION KLIPPER
Descargar klipper**********.cfg.

¡¡EN CASO DE SER NECESARIO!! CAMBIAMOS LOS PUERTOS DE LOS *****_STEPPER POR LOS DEFINIDOS EN NUESTRA PLACA PARA KLIPPER.

Subirlo a la impresora desde mainsail o fluidd.

Añadir [include klipper*********.cfg] en printer.cfg.

Verificar la distancia que necesita para descargar, en caso de necesitar cambio, modificamos en _DESCARGA_FILAMENTO -300 por la distancia necesaria.

Guardamos y reiniciamos.

Para poder pobras sin estar en una impresion, calentamos hotend a 220º y hacemos homing.

¡¡¡RECOMENDACION!!!

HAZ LAS PRIMERAS PRUEBAS SIN FILAMENTO, PARA VER QUE LOS MOTORES DE CARGA Y DESCARGA SE MUEVE, QUE EJECUTA QUIT Y LOAD MATERIAL CUANDO CORRESPONDE.
