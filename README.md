# Quintana Roo: law history in git

The law of the State of Quintana Roo (Estado Libre y Soberano de Quintana Roo, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-roo/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

140 ordenamientos with 1206 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE QUINTANA ROO | 159 | as first published, then each reform: 12 January 1975 to 23 June 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE QUINTANA ROO | 60 | as first published, then each reform: 7 November 1980 to 23 July 2026 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO LIBRE Y SOBERANO DE QUINTANA ROO | 25 | as first published, then each reform: 9 January 1981 to 29 May 2026 |
| `codigo-de-procedimientos-y-justicia-administrativa/` | CODIGO DE PROCEDIMIENTOS Y JUSTICIA ADMINISTRATIVA DEL ESTADO DE QUINTANA ROO | 1 | as first published: 9 October 2024 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE QUINTANA ROO | 44 | as first published, then each reform: 14 January 1995 to 16 December 2025 |
| `codigo-fiscal-municipal/` | CODIGO FISCAL MUNICIPAL DEL ESTADO DE QUINTANA ROO | 5 | oldest version available, then each reform: 16 January 2013 to 10 December 2025 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO LIBRE Y SOBERANO DE QUINTANA ROO | 120 | as first published, then each reform: 13 April 1991 to 11 April 2026 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA DEL ESTADO DE QUINTANA ROO | 20 | as first published, then each reform: 28 November 2007 to 11 December 2025 |
| `ley-de-accion-de-cambio-climatico-en-el-estado-de-quintana-r/` | LEY DE ACCION DE CAMBIO CLIMATICO EN EL ESTADO DE QUINTANA ROO | 7 | as first published, then each reform: 30 March 2012 to 17 June 2023 |
| `ley-de-acciones-urbanisticas/` | LEY DE ACCIONES URBANISTICAS DEL ESTADO DE QUINTANA ROO | 6 | as first published, then each reform: 17 August 2018 to 29 May 2026 |
| `ley-de-adopcion/` | LEY DE ADOPCION DEL ESTADO DE QUINTANA ROO | 6 | as first published, then each reform: 1 July 2009 to 6 June 2024 |
| `ley-de-adquisiciones-arrendamientos-y-prestacion-de-servicio/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y PRESTACION DE SERVICIOS RELACIONADOS CON BIENES MUEBLES DEL ESTADO DE QUINTANA ROO | 5 | as first published, then each reform: 16 February 1995 to 17 July 2021 |
| `ley-de-agua-potable-y-alcantarillado/` | LEY DE AGUA POTABLE Y ALCANTARILLADO DEL ESTADO DE QUINTANA ROO | 8 | as first published, then each reform: 7 October 1981 to 29 May 2026 |
| `ley-de-amnistia/` | LEY DE AMNISTIA PARA EL ESTADO DE QUINTANA ROO | 1 | as first published: 22 December 2021 |
| `ley-de-archivos/` | LEY DE ARCHIVOS DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 14 July 2023 to 23 December 2023 |
| `ley-de-asentamientos-humanos-ordenamiento-territorial-y-desa/` | LEY DE ASENTAMIENTOS HUMANOS, ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO DEL ESTADO DE QUINTANA ROO | 11 | as first published, then each reform: 17 August 2018 to 29 May 2026 |
| `ley-de-asistencia-social/` | LEY DE ASISTENCIA SOCIAL PARA EL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 16 December 1998 to 17 November 2015 |
| `ley-de-asistencia-y-prevencion-de-la-violencia-familiar/` | LEY DE ASISTENCIA Y PREVENCION DE LA VIOLENCIA FAMILIAR PARA EL ESTADO DE QUINTANA ROO -ANTES VIOLENCIA INTRAFAMILIAR- | 6 | as first published, then each reform: 16 June 2000 to 8 September 2022 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO-PRIVADAS PARA EL ESTADO Y MUNICIPIOS DE QUINTANA ROO | 1 | as first published: 30 June 2017 |
| `ley-de-bibliotecas/` | LEY DE BIBLIOTECAS DEL ESTADO DE QUINTANA ROO | 4 | as first published, then each reform: 13 December 2010 to 8 June 2023 |
| `ley-de-catastro/` | LEY DE CATASTRO DEL ESTADO DE QUINTANA ROO | 4 | as first published, then each reform: 12 March 2008 to 1 August 2024 |
| `ley-de-conservacion-mantenimiento-proteccion-y-desarrollo-de/` | LEY DE CONSERVACION, MANTENIMIENTO, PROTECCION Y DESARROLLO DEL ARBOLADO URBANO DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 25 February 2018 to 9 September 2022 |
| `ley-de-consulta-a-los-pueblos-y-comunidades-indigenas-y-afro/` | LEY DE CONSULTA A LOS PUEBLOS Y COMUNIDADES INDIGENAS Y AFROMEXICANAS DEL ESTADO DE QUINTANA ROO | 1 | as first published: 25 August 2022 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL DEL ESTADO DE QUINTANA ROO | 5 | as first published, then each reform: 1 January 2021 to 30 May 2026 |
| `ley-de-cultura-de-la-legalidad/` | LEY DE CULTURA DE LA LEGALIDAD DEL ESTADO LIBRE Y SOBERANO DE QUINTANA ROO | 3 | as first published, then each reform: 1 January 2013 to 9 May 2025 |
| `ley-de-cultura-y-las-artes/` | LEY DE CULTURA Y LAS ARTES DEL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 17 December 2007 to 29 June 2017 |
| `ley-de-cuotas-y-tarifas-para-los-servicios-publicos-de-agua/` | LEY DE CUOTAS Y TARIFAS PARA LOS SERVICIOS PUBLICOS DE AGUA POTABLE Y ALCANTARILLADO, TRATAMIENTO Y DISPOSICION DE AGUAS RESIDUALES DEL ESTADO DE QUINTANA ROO | 8 | as first published, then each reform: 3 July 2008 to 29 May 2026 |
| `ley-de-derechos/` | LEY DE DERECHOS DEL ESTADO DE QUINTANA ROO | 16 | as first published, then each reform: 3 January 2019 to 18 December 2025 |
| `ley-de-derechos-cultura-y-organizacion-indigena/` | LEY DE DERECHOS, CULTURA Y ORGANIZACION INDIGENA DEL ESTADO DE QUINTANA ROO | 5 | as first published, then each reform: 31 July 1998 to 25 August 2022 |
| `ley-de-desarrollo-economico-y-competitividad/` | LEY DE DESARROLLO ECONOMICO Y COMPETITIVIDAD PARA EL ESTADO DE QUINTANA ROO | 14 | as first published, then each reform: 18 December 2007 to 17 December 2025 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE PARA EL ESTADO DE QUINTANA ROO | 1 | as first published: 28 November 2023 |
| `ley-de-desarrollo-rural-sustentable/` | LEY DE DESARROLLO RURAL SUSTENTABLE DEL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 13 August 2019 to 22 December 2023 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA DEL ESTADO DE QUINTANA ROO Y SUS MUNICIPIOS | 1 | as first published: 3 November 2016 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE QUINTANA ROO | 9 | as first published, then each reform: 28 April 2022 to 11 July 2024 |
| `ley-de-entrega-y-recepcion-de-los-poderes-publicos-ayuntamie/` | LEY DE ENTREGA Y RECEPCION DE LOS PODERES PUBLICOS, AYUNTAMIENTOS, ORGANOS PUBLICOS AUTONOMOS Y DE LAS ENTIDADES DE LA ADMINISTRACION PUBLICA PARAESTATAL DEL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 17 December 2021 to 25 July 2024 |
| `ley-de-expropiacion-ocupacion-temporal-y-limitacion-de-domin/` | LEY DE EXPROPIACION, OCUPACION TEMPORAL Y LIMITACION DE DOMINIO DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 17 January 2025 to 2 April 2025 |
| `ley-de-filmaciones-y-produccion-audiovisual/` | LEY DE FILMACIONES Y PRODUCCION AUDIOVISUAL DEL ESTADO DE QUINTANA ROO | 1 | as first published: 10 April 2024 |
| `ley-de-fiscalizacion-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION Y RENDICION DE CUENTAS DEL ESTADO DE QUINTANA ROO | 6 | as first published, then each reform: 20 July 2017 to 10 October 2025 |
| `ley-de-fomento-a-la-lectura-y-el-libro/` | LEY DE FOMENTO A LA LECTURA Y EL LIBRO DEL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 1 January 2013 to 4 November 2017 |
| `ley-de-fomento-a-las-actividades-realizadas-por-las-organiza/` | LEY DE FOMENTO A LAS ACTIVIDADES REALIZADAS POR LAS ORGANIZACIONES CIVILES PARA EL ESTADO DE QUINTANA ROO | 4 | as first published, then each reform: 23 March 2011 to 18 March 2023 |
| `ley-de-fomento-al-primer-empleo/` | LEY DE FOMENTO AL PRIMER EMPLEO PARA EL ESTADO DE QUINTANA ROO | 1 | as first published: 9 October 2014 |
| `ley-de-fomento-para-la-nutricion-y-el-combate-del-sobrepeso/` | LEY DE FOMENTO PARA LA NUTRICION Y EL COMBATE DEL SOBREPESO, OBESIDAD, DIABETES MELLITUS Y TRASTORNOS DE LA CONDUCTA ALIMENTARIA - ANTES LEY DE FOMENTO PARA LA NUTRICION Y EL COMBATE DEL SOBREPESO, OBESIDAD Y TRASTORNOS DE LA CONDUCTA ALIMENTARIA -- PARA EL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 15 November 2014 to 9 April 2022 |
| `ley-de-fomento-y-desarrollo-pecuario/` | LEY DE FOMENTO Y DESARROLLO PECUARIO PARA EL ESTADO DE QUINTANA ROO | 1 | as first published: 3 July 2010 |
| `ley-de-hacienda-de-los-municipios/` | LEY DE HACIENDA DE LOS MUNICIPIOS DEL ESTADO DE QUINTANA ROO | 35 | as first published, then each reform: 1 January 1998 to 5 June 2024 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO DE QUINTANA ROO | 10 | as first published, then each reform: 1 January 2020 to 16 December 2025 |
| `ley-de-hacienda-del-municipio-de-bacalar/` | LEY DE HACIENDA DEL MUNICIPIO DE BACALAR, DEL ESTADO DE QUINTANA ROO | 4 | as first published, then each reform: 27 December 2021 to 21 December 2023 |
| `ley-de-hacienda-del-municipio-de-felipe-carrillo-puerto/` | LEY DE HACIENDA DEL MUNICIPIO DE FELIPE CARRILLO PUERTO DEL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 21 December 2023 to 16 December 2024 |
| `ley-de-hacienda-del-municipio-de-isla-mujeres/` | LEY DE HACIENDA DEL MUNICIPIO DE ISLA MUJERES DEL ESTADO DE QUINTANA ROO | 10 | as first published, then each reform: 29 November 2018 to 10 December 2025 |
| `ley-de-hacienda-del-municipio-de-lazaro-cardenas/` | LEY DE HACIENDA DEL MUNICIPIO DE LAZARO CARDENAS DEL ESTADO DE QUINTANA ROO | 11 | as first published, then each reform: 15 December 2015 to 10 December 2025 |
| `ley-de-hacienda-del-municipio-de-othon-p-blanco/` | LEY DE HACIENDA DEL MUNICIPIO DE OTHON P. BLANCO DEL ESTADO DE QUINTANA ROO | 6 | as first published, then each reform: 31 December 2018 to 11 December 2025 |
| `ley-de-hacienda-del-municipio-de-tulum/` | LEY DE HACIENDA DEL MUNICIPIO DE TULUM DEL ESTADO DE QUINTANA ROO | 4 | as first published, then each reform: 22 December 2022 to 10 December 2025 |
| `ley-de-humanidades-ciencias-tecnologias-e-innovacion/` | LEY DE HUMANIDADES, CIENCIAS, TECNOLOGIAS E INNOVACION DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 6 March 2024 to 18 April 2024 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE QUINTANA ROO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-instituciones-y-procedimientos-electorales/` | LEY DE INSTITUCIONES Y PROCEDIMIENTOS ELECTORALES PARA EL ESTADO DE QUINTANA ROO | 20 | as first published, then each reform: 21 September 2017 to 30 May 2026 |
| `ley-de-justicia-alternativa/` | LEY DE JUSTICIA ALTERNATIVA DEL ESTADO DE QUINTANA ROO | 1 | as first published: 14 August 2021 |
| `ley-de-justicia-indigena/` | LEY DE JUSTICIA INDIGENA DEL ESTADO DE QUINTANA ROO | 5 | as first published, then each reform: 14 August 1997 to 3 January 2013 |
| `ley-de-la-comision-de-los-derechos-humanos/` | LEY DE LA COMISION DE LOS DERECHOS HUMANOS DEL ESTADO DE QUINTANA ROO -ANTES LEY DE LA COMISION DE DERECHOS HUMANOS DEL ESTADO DE QUINTANA ROO- | 11 | as first published, then each reform: 14 December 2002 to 10 October 2024 |
| `ley-de-la-infraestructura-fisica-educativa/` | LEY DE LA INFRAESTRUCTURA FISICA EDUCATIVA DEL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 29 June 2010 to 25 April 2024 |
| `ley-de-la-juventud/` | LEY DE LA JUVENTUD DEL ESTADO LIBRE Y SOBERANO DE QUINTANA ROO | 13 | as first published, then each reform: 12 April 2013 to 11 December 2025 |
| `ley-de-las-entidades-de-la-administracion-publica-paraestata/` | LEY DE LAS ENTIDADES DE LA ADMINISTRACION PUBLICA PARAESTATAL DEL ESTADO DE QUINTANA ROO | 7 | as first published, then each reform: 23 January 2003 to 23 January 2025 |
| `ley-de-los-derechos-de-las-personas-adultas-mayores/` | LEY DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES DEL ESTADO DE QUINTANA ROO | 4 | as first published, then each reform: 10 August 2007 to 11 July 2024 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE QUINTANA ROO | 9 | as first published, then each reform: 30 April 2015 to 10 December 2024 |
| `ley-de-los-municipios/` | LEY DE LOS MUNICIPIOS DEL ESTADO DE QUINTANA ROO | 50 | as first published, then each reform: 21 December 2004 to 30 May 2026 |
| `ley-de-los-trabajadores-al-servicio-de-los-poderes-legislati/` | LEY DE LOS TRABAJADORES AL SERVICIO DE LOS PODERES LEGISLATIVO, EJECUTIVO Y JUDICIAL DE LOS AYUNTAMIENTOS Y ORGANISMOS DESCENTRALIZADOS DEL ESTADO DE QUINTANA ROO | 18 | as first published, then each reform: 13 June 1978 to 17 June 2023 |
| `ley-de-movilidad/` | LEY DE MOVILIDAD DEL ESTADO DE QUINTANA ROO | 19 | as first published, then each reform: 12 September 2018 to 6 March 2026 |
| `ley-de-obras-publicas-y-servicios-relacionados-con-las-misma/` | LEY DE OBRAS PUBLICAS Y SERVICIOS RELACIONADOS CON LAS MISMAS DEL ESTADO DE QUINTANA ROO | 8 | as first published, then each reform: 11 December 2010 to 9 May 2025 |
| `ley-de-ordenamiento-civico/` | LEY DE ORDENAMIENTO CIVICO DEL ESTADO DE QUINTANA ROO | 4 | as first published, then each reform: 5 May 2014 to 7 June 2024 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 23 March 2018 to 29 May 2019 |
| `ley-de-pesca-responsable-y-acuacultura/` | LEY DE PESCA RESPONSABLE Y ACUACULTURA PARA EL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 10 April 2013 to 1 January 2023 |
| `ley-de-planeacion-para-el-desarrollo/` | LEY DE PLANEACION PARA EL DESARROLLO DEL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 16 August 2022 to 20 August 2025 |
| `ley-de-prestacion-de-servicios-inmobiliarios/` | LEY DE PRESTACION DE SERVICIOS INMOBILIARIOS DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 7 September 2024 to 17 December 2025 |
| `ley-de-presupuesto-y-gasto-publico/` | LEY DE PRESUPUESTO Y GASTO PUBLICO DEL ESTADO DE QUINTANA ROO -- ANTES LEY DE PRESUPUESTO, CONTABILIDAD Y GASTO PUBLICO DEL ESTADO DE QUINTANA ROO -- | 7 | as first published, then each reform: 17 December 1993 to 2 April 2024 |
| `ley-de-prevencion-del-delito/` | LEY DE PREVENCION DEL DELITO PARA EL ESTADO DE QUINTANA ROO | 4 | as first published, then each reform: 7 September 2013 to 19 December 2023 |
| `ley-de-prevencion-atencion-integral-y-control-para-el-vih/` | LEY DE PREVENCION, ATENCION INTEGRAL Y CONTROL PARA EL VIH DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 14 July 2022 to 11 December 2025 |
| `ley-de-profesiones/` | LEY DE PROFESIONES DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 16 June 1998 to 6 October 2023 |
| `ley-de-propiedad-en-condominio-de-inmuebles/` | LEY DE PROPIEDAD EN CONDOMINIO DE INMUEBLES DEL ESTADO DE QUINTANA ROO | 5 | as first published, then each reform: 1 December 2010 to 13 November 2021 |
| `ley-de-proteccion-a-la-salud-de-los-no-fumadores/` | LEY DE PROTECCION A LA SALUD DE LOS NO FUMADORES PARA EL ESTADO DE QUINTANA ROO | 1 | as first published: 1 January 2008 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL DEL ESTADO DE QUINTANA ROO | 8 | as first published, then each reform: 2 June 2009 to 22 December 2023 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE QUINTANA ROO | 1 | as first published: 26 November 2025 |
| `ley-de-proteccion-y-bienestar-animal/` | LEY DE PROTECCION Y BIENESTAR ANIMAL DEL ESTADO DE QUINTANA ROO | 8 | as first published, then each reform: 26 November 2019 to 11 April 2026 |
| `ley-de-proteccion-y-fomento-apicola/` | LEY DE PROTECCION Y FOMENTO APICOLA DEL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 16 July 2022 to 22 December 2023 |
| `ley-de-quemas-y-prevencion-de-incendios-forestales/` | LEY DE QUEMAS Y PREVENCION DE INCENDIOS FORESTALES PARA EL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 1 May 2012 to 17 June 2014 |
| `ley-de-responsabilidad-ambiental/` | LEY DE RESPONSABILIDAD AMBIENTAL DEL ESTADO DE QUINTANA ROO | 1 | as first published: 29 April 2022 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE QUINTANA ROO | 1 | as first published: 21 February 2021 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS DEL ESTADO DE QUINTANA ROO Y SUS MUNICIPIOS | 1 | as first published: 15 October 2024 |
| `ley-de-responsabilidades-de-los-servidores-publicos/` | LEY DE RESPONSABILIDADES DE LOS SERVIDORES PUBLICOS DEL ESTADO DE QUINTANA ROO | 5 | as first published, then each reform: 1 October 2002 to 7 September 2013 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE QUINTANA ROO | 23 | as first published, then each reform: 29 January 1995 to 17 December 2025 |
| `ley-de-salud-mental/` | LEY DE SALUD MENTAL DEL ESTADO DE QUINTANA ROO | 1 | as first published: 20 January 2021 |
| `ley-de-seguridad-ciudadana/` | LEY DE SEGURIDAD CIUDADANA DEL ESTADO DE QUINTANA ROO | 7 | as first published, then each reform: 21 April 2023 to 6 March 2026 |
| `ley-de-seguridad-escolar-integral/` | LEY DE SEGURIDAD ESCOLAR INTEGRAL DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 27 April 2022 to 11 December 2025 |
| `ley-de-seguridad-social-de-los-servidores-publicos-del-gobie/` | LEY DE SEGURIDAD SOCIAL DE LOS SERVIDORES PUBLICOS DEL GOBIERNO DEL ESTADO, MUNICIPIOS Y ORGANISMOS PUBLICOS DESCENTRALIZADOS DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 13 June 1989 to 8 June 2023 |
| `ley-de-servicio-publico-de-carrera/` | LEY DE SERVICIO PUBLICO DE CARRERA DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 16 February 2002 to 17 July 2021 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE QUINTANA ROO | 1 | as first published: 26 November 2025 |
| `ley-de-transporte-ferroviario/` | LEY DE TRANSPORTE FERROVIARIO PARA EL ESTADO DE QUINTANA ROO | 1 | as first published: 9 January 2004 |
| `ley-de-turismo/` | LEY DE TURISMO DEL ESTADO DE QUINTANA ROO | 12 | as first published, then each reform: 29 June 2010 to 16 December 2025 |
| `ley-de-valuacion/` | LEY DE VALUACION PARA EL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 1 May 2003 to 1 August 2024 |
| `ley-de-victimas/` | LEY DE VICTIMAS DEL ESTADO DE QUINTANA ROO | 9 | as first published, then each reform: 8 April 2014 to 11 December 2025 |
| `ley-de-vida-silvestre/` | LEY DE VIDA SILVESTRE PARA EL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 26 September 2012 to 20 August 2013 |
| `ley-de-vivienda/` | LEY DE VIVIENDA DEL ESTADO DE QUINTANA ROO | 8 | as first published, then each reform: 22 December 2010 to 29 May 2026 |
| `ley-del-colegio-de-bachilleres/` | LEY DEL COLEGIO DE BACHILLERES DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 23 December 2023 to 18 April 2024 |
| `ley-del-consejo-estatal-de-poblacion-de-quintana-roo/` | LEY DEL CONSEJO ESTATAL DE POBLACION DE QUINTANA ROO | 2 | as first published, then each reform: 31 December 2002 to 20 August 2013 |
| `ley-del-equilibrio-ecologico-y-la-proteccion-al-ambiente/` | LEY DEL EQUILIBRIO ECOLOGICO Y LA PROTECCION AL AMBIENTE DEL ESTADO DE QUINTANA ROO | 14 | as first published, then each reform: 30 June 2001 to 21 August 2025 |
| `ley-del-fondo-para-el-mejoramiento-en-la-administracion-e-im/` | LEY DEL FONDO PARA EL MEJORAMIENTO EN LA ADMINISTRACION E IMPARTICION DE JUSTICIA -- ANTES LEY DEL FONDO PARA EL MEJORAMIENTO DE LA ADMINISTRACION DE JUSTICIA -- DEL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 15 January 1996 to 23 June 2026 |
| `ley-del-impuesto-a-las-erogaciones-en-juegos-y-concursos/` | LEY DEL IMPUESTO A LAS EROGACIONES EN JUEGOS Y CONCURSOS DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 18 December 2016 to 16 December 2025 |
| `ley-del-impuesto-al-hospedaje/` | LEY DEL IMPUESTO AL HOSPEDAJE DEL ESTADO DE QUINTANA ROO | 10 | as first published, then each reform: 30 December 2017 to 16 December 2025 |
| `ley-del-impuesto-sobre-adquisicion-de-bienes-inmuebles-de-lo/` | LEY DEL IMPUESTO SOBRE ADQUISICION DE BIENES INMUEBLES DE LOS MUNICIPIOS DEL ESTADO DE QUINTANA ROO | 9 | as first published, then each reform: 3 October 2011 to 27 December 2021 |
| `ley-del-impuesto-sobre-nominas/` | LEY DEL IMPUESTO SOBRE NOMINAS DEL ESTADO DE QUINTANA ROO | 8 | as first published, then each reform: 1 January 2016 to 16 December 2025 |
| `ley-del-instituto-de-defensoria-publica/` | LEY DEL INSTITUTO DE DEFENSORIA PUBLICA DEL ESTADO DE QUINTANA ROO | 6 | as first published, then each reform: 23 November 2013 to 5 June 2024 |
| `ley-del-instituto-para-el-desarrollo-y-financiamiento/` | LEY DEL INSTITUTO PARA EL DESARROLLO Y FINANCIAMIENTO DEL ESTADO DE QUINTANA ROO | 1 | as first published: 23 December 2023 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE QUINTANA ROO | 7 | as first published, then each reform: 3 July 2019 to 12 August 2025 |
| `ley-del-patrimonio-cultural/` | LEY DEL PATRIMONIO CULTURAL DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 7 September 2013 to 24 December 2014 |
| `ley-del-patrimonio/` | LEY DEL PATRIMONIO DEL ESTADO DE QUINTANA ROO | 7 | as first published, then each reform: 29 March 2005 to 9 May 2025 |
| `ley-del-periodico-oficial/` | LEY DEL PERIODICO OFICIAL DEL ESTADO DE QUINTANA ROO | 1 | as first published: 30 January 2021 |
| `ley-del-secretariado-ejecutivo-del-sistema-estatal-de-seguri/` | LEY DEL SECRETARIADO EJECUTIVO DEL SISTEMA ESTATAL DE SEGURIDAD CIUDADANA DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 16 October 2024 to 12 February 2025 |
| `ley-del-servicio-de-administracion-tributaria/` | LEY DEL SERVICIO DE ADMINISTRACION TRIBUTARIA DEL ESTADO DE QUINTANA ROO | 9 | as first published, then each reform: 3 January 2019 to 21 March 2026 |
| `ley-del-sistema-anticorrupcion/` | LEY DEL SISTEMA ANTICORRUPCION DEL ESTADO DE QUINTANA ROO | 6 | as first published, then each reform: 20 July 2017 to 24 June 2026 |
| `ley-en-materia-de-declaracion-especial-de-ausencia-para-pers/` | LEY EN MATERIA DE DECLARACION ESPECIAL DE AUSENCIA PARA PERSONAS DESAPARECIDAS DEL ESTADO DE QUINTANA ROO | 1 | as first published: 30 August 2025 |
| `ley-en-materia-de-trata-de-personas/` | LEY EN MATERIA DE TRATA DE PERSONAS DEL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 24 December 2014 to 11 December 2025 |
| `ley-estatal-de-cultura-fisica-y-deporte/` | LEY ESTATAL DE CULTURA FISICA Y DEPORTE | 6 | as first published, then each reform: 12 March 2008 to 4 November 2023 |
| `ley-estatal-de-medios-de-impugnacion-en-materia-electoral/` | LEY ESTATAL DE MEDIOS DE IMPUGNACION EN MATERIA ELECTORAL | 10 | as first published, then each reform: 28 August 2002 to 9 September 2020 |
| `ley-organica-de-justicia-en-materia-de-faltas-de-policia-y-b/` | LEY ORGANICA DE JUSTICIA EN MATERIA DE FALTAS DE POLICIA Y BUEN GOBIERNO DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 1 April 1989 to 10 April 2013 |
| `ley-organica-de-la-administracion-publica/` | LEY ORGANICA DE LA ADMINISTRACION PUBLICA DEL ESTADO DE QUINTANA ROO | 35 | as first published, then each reform: 20 August 2013 to 21 March 2026 |
| `ley-organica-de-la-fiscalia-especializada-en-combate-a-la-co/` | LEY ORGANICA DE LA FISCALIA ESPECIALIZADA EN COMBATE A LA CORRUPCION DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 11 January 2025 to 17 December 2025 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE QUINTANA ROO | 11 | as first published, then each reform: 13 September 2019 to 11 December 2025 |
| `ley-organica-de-la-secretaria-de-seguridad-publica/` | LEY ORGANICA DE LA SECRETARIA DE SEGURIDAD PUBLICA DEL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 8 April 2014 to 17 December 2021 |
| `ley-organica-de-la-universidad-de-quintana-roo/` | LEY ORGANICA DE LA UNIVERSIDAD DE QUINTANA ROO | 6 | as first published, then each reform: 15 September 1994 to 24 March 2022 |
| `ley-organica-de-la-universidad-judicial-del-poder-judicial/` | LEY ORGANICA DE LA UNIVERSIDAD JUDICIAL DEL PODER JUDICIAL DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 5 February 2025 to 13 August 2025 |
| `ley-organica-del-centro-de-conciliacion-laboral/` | LEY ORGANICA DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 23 June 2021 to 7 October 2021 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DE ESTADO DE QUINTANA ROO | 1 | as first published: 13 August 2025 |
| `ley-organica-del-poder-legislativo/` | LEY ORGANICA DEL PODER LEGISLATIVO DEL ESTADO DE QUINTANA ROO | 18 | as first published, then each reform: 15 June 2019 to 13 May 2026 |
| `ley-organica-del-sistema-para-el-desarrollo-integral-de-la-f/` | LEY ORGANICA DEL SISTEMA PARA EL DESARROLLO INTEGRAL DE LA FAMILIA DEL ESTADO DE QUINTANA ROO | 5 | as first published, then each reform: 16 January 1985 to 8 June 2023 |
| `ley-organica-del-tribunal-de-justicia-administrativa-y-antic/` | LEY ORGANICA DEL TRIBUNAL DE JUSTICIA ADMINISTRATIVA Y ANTICORRUPCION DEL ESTADO DE QUINTANA ROO | 1 | as first published: 7 October 2024 |
| `ley-para-el-desarrollo-social/` | LEY PARA EL DESARROLLO SOCIAL DEL ESTADO DE QUINTANA ROO | 4 | as first published, then each reform: 31 May 2007 to 18 March 2023 |
| `ley-para-el-desarrollo-y-la-inclusion-de-las-personas-con-di/` | LEY PARA EL DESARROLLO Y LA INCLUSION DE LAS PERSONAS CON DISCAPACIDAD DEL ESTADO DE QUINTANA ROO | 6 | as first published, then each reform: 31 July 2013 to 2 April 2025 |
| `ley-para-el-fomento-de-la-cultura-de-donacion-voluntaria-de/` | LEY PARA EL FOMENTO DE LA CULTURA DE DONACION VOLUNTARIA DE SANGRE DEL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 10 June 2014 to 31 October 2015 |
| `ley-para-el-fomento-de-la-cultura-del-cuidado-del-agua-en-el/` | LEY PARA EL FOMENTO DE LA CULTURA DEL CUIDADO DEL AGUA EN EL ESTADO DE QUINTANA ROO | 2 | as first published, then each reform: 7 September 2013 to 17 July 2021 |
| `ley-para-el-fomento-de-la-eficiencia-energetica-y-del-aprove/` | LEY PARA EL FOMENTO DE LA EFICIENCIA ENERGETICA Y DEL APROVECHAMIENTO DE LAS FUENTES DE ENERGIA RENOVABLES EN EL ESTADO DE QUINTANA ROO -- ANTES LEY PARA EL FOMENTO Y APROVECHAMIENTO DE LAS FUENTES DE ENERGIA RENOVABLES EN EL ESTADO DE QUINTANA ROO -- | 3 | as first published, then each reform: 7 September 2013 to 17 July 2021 |
| `ley-para-el-fomento-de-las-sociedades-cooperativas-en-el-est/` | LEY PARA EL FOMENTO DE LAS SOCIEDADES COOPERATIVAS EN EL ESTADO DE QUINTANA ROO | 3 | as first published, then each reform: 20 June 2013 to 18 March 2023 |
| `ley-para-fomentar-la-donacion-altruista-de-alimentos-en-el-e/` | LEY PARA FOMENTAR LA DONACION ALTRUISTA DE ALIMENTOS EN EL ESTADO DE QUINTANA ROO | 1 | as first published: 30 April 2013 |
| `ley-para-la-administracion-de-bienes-asegurados-abandonados/` | LEY PARA LA ADMINISTRACION DE BIENES ASEGURADOS, ABANDONADOS Y DECOMISADOS DEL ESTADO DE QUINTANA ROO | 1 | as first published: 10 December 2014 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Cancun, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
