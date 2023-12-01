# Refrigerador Portátil
**Laboratorio de Electrónica Digital I**

Integrantes:

**- Theylor Andrés Amaya Villabon** : Ingeniería Mecatrónica.

**- María Angélica Lesmes Calderón** : Ingeniería Electrónica 

**- Diomedes López López** : Ingeniería Electrónica

Profesores:

**- Diego Alexander Tibaduiza Burgos**

**- Johnny German Cubides Castro**

Universidad Nacional de Colombia

Facultad de Ingeniería

## Planteamiento del problema
Existe una creciente demanda de refrigeración portátil para diversas aplicaciones, como viajes, campamentos y trayectos largos en vehiculos, donde mantener alimentos, bebidas y medicamentos a temperaturas especificas es esencial. 

Por ello, nuestro proyecto es desarrollar un refrigerador portátil eficiente y asequible que pueda ser alimentado con una fuente de energía de corriente continua, como una batería o la toma de corriente de un vehículo a través del encendedor de cigarrillos. 

##Introducción:

En un mundo en constante movimiento y cambio, la necesidad de contar con soluciones de refrigeración portátil se ha vuelto esencial en diversas situaciones, desde viajes largos y campamentos hasta entornos con acceso limitado a la energía eléctrica. La presente investigación se centra en el desarrollo de un Refrigerador Portátil eficiente y asequible, diseñado para funcionar con fuentes de energía de corriente continua, como baterías o tomas de corriente de vehículos a través del encendedor de cigarrillos. Este proyecto es llevado a cabo por un grupo de estudiantes de ingeniería de la Universidad Nacional de Colombia, en colaboración con sus profesores, con el objetivo de abordar una necesidad apremiante en la sociedad colombiana.

Marco Teórico:

El marco teórico de este informe se apoya en varios aspectos fundamentales relacionados con la problemática y la solución propuesta:

Refrigeración Portátil: La refrigeración portátil se ha convertido en una demanda creciente en una variedad de contextos. Desde la conservación de alimentos y bebidas durante viajes hasta la preservación de medicamentos sensibles a la temperatura, la capacidad de mantener productos a temperaturas específicas sin depender de la red eléctrica tradicional se ha vuelto cada vez más relevante.

Análisis PESTAL: Para comprender mejor el entorno en el que se desarrolla el proyecto, se realiza un análisis PESTAL que abarca factores políticos, económicos, sociales, tecnológicos, ambientales y legales. Este análisis identifica las influencias y oportunidades clave relacionadas con la refrigeración portátil en Colombia, desde posibles regulaciones gubernamentales hasta el impacto en la salud alimentaria y el acceso limitado a la energía eléctrica.

Antecedentes: Los datos de la Encuesta Nacional de Uso del Tiempo (ENUT) del Departamento Administrativo Nacional de Estadística (DANE) resaltan la importancia de este proyecto al revelar que una parte significativa de los hogares colombianos carece de sistemas de refrigeración. Además, la falta de acceso a la energía eléctrica en algunas áreas del país enfatiza aún más la necesidad de soluciones de refrigeración independientes de la red eléctrica.

Objetivos: El objetivo general del proyecto es desarrollar un refrigerador portátil accesible y eficiente, diseñado tanto para personas sin acceso a energía eléctrica como para aquellos que no disponen de sistemas de refrigeración en sus hogares. Los objetivos específicos incluyen la creación de un diseño asequible y la optimización de la eficiencia energética del refrigerador mediante la gestión dinámica de la potencia suministrada.

Presupuesto: El presupuesto detallado proporciona una visión clara de los recursos financieros necesarios para llevar a cabo el proyecto, incluyendo componentes electrónicos clave como FPGA, Arduino Uno y sistemas de refrigeración termoeléctricos Peltier, entre otros.

Diagramas, Simulación y Fotografías: Los diagramas de caja negra y en digital, junto con la simulación y las fotografías del montaje, ofrecen una visión visual del proceso de desarrollo y funcionamiento del refrigerador portátil.

Vídeo de Funcionamiento: Se proporciona un enlace a un vídeo que muestra el funcionamiento práctico del refrigerador portátil, lo que permite una comprensión más completa de su operación.

## Análisis pestal

Político:

- Regulaciones gubernamentales: El gobierno colombiano podría tener políticas que fomenten la eficiencia energética y la adopción de tecnologías sostenibles, lo que podría influir en la viabilidad y apoyo a proyectos relacionados con la refrigeración.

- Acceso a subsidios: Existe la posibilidad de que se otorguen subsidios o incentivos para ayudar a las familias de bajos ingresos a adquirir sistemas de refrigeración asequibles.

Económico:

- Desigualdad económica: La falta de sistemas de refrigeración puede ser un reflejo de la disparidad económica en Colombia, ya que el costo de las neveras puede ser inaccesible para muchos hogares.

- Oportunidades de mercado: La creación de soluciones de refrigeración accesibles y sostenibles podría generar oportunidades económicas y de empleo en el país

Social:

- Salud y seguridad alimentaria: La falta de sistemas de refrigeración podría afectar negativamente la calidad de los alimentos y la seguridad alimentaria en hogares sin acceso a refrigeración.

- Necesidades médicas: La incapacidad de mantener medicamentos a temperaturas adecuadas puede tener graves implicaciones para las personas con necesidades médicas específicas, como diabéticos que requieren insulina.

Tecnológico:

- Avances en tecnología termoeléctrica: Los avances en la tecnología de celdas Peltier o sistemas termoeléctricos pueden hacer que la refrigeración sin red eléctrica sea más viable y asequible.

- Fuentes de energía alternativa: La tecnología de energía renovable puede proporcionar soluciones sostenibles para abordar la falta de acceso a la energía eléctrica.

Ambiental:

- Sostenibilidad: La adopción de sistemas de refrigeración sostenibles y energéticamente eficientes puede contribuir a la reducción del impacto ambiental y al uso responsable de los recursos energéticos.

Legal:

- Regulaciones de seguridad: Los proyectos de refrigeración deben cumplir con regulaciones de seguridad y calidad para garantizar la protección de los consumidores y la integridad de los productos almacenados.
  
- Derechos de propiedad intelectual: Si se están desarrollando soluciones tecnológicas nuevas, es importante considerar las implicaciones legales en términos de patentes y derechos de propiedad intelectual.

## Antecedentes

En los hogares colombianos, la disponibilidad de sistemas de refrigeración es un asunto crítico que requiere atención inmediata. Según datos recopilados por la Encuesta Nacional de Uso del Tiempo (ENUT) del Departamento Administrativo Nacional de Estadística (DANE) en el año 2022, se revela que aproximadamente el 74% de los hogares colombianos en el dominio geográfico cuentan con un dispositivo de refrigeración, generalmente una nevera. Si bien este porcentaje podría sugerir 
un acceso generalizado a sistemas de enfriamiento, es esencial destacar que aún existe un número significativo de hogares que carecen de cualquier sistema de refrigeración. 

Por otro lado, Colombia enfrenta un desafío adicional relacionado con la disponibilidad de energía eléctrica. Aproximadamente el 50% del territorio del país todavía no está conectado a las redes eléctricas principales, y gran parte de esta área se encuentra en la zona sur del país. 

## Objetivos

**General:**

Desarrollar un refrigerador portátil para personas que no tienen disponibilidad de energía eléctrica y también para aquellos que en sus hogares carecen de cualquier sistema de refrigración.

**Específicos:** 

- Obtener un diseño accesible y asequible.
- Optimizar la eficiencia energética del refrigerador ajustandoo dinámicamente la potencia suministrada en función de las necesidades térmicas requeridas.

## Presupuesto 


| Elemento                             | Precio      |
| ------------------------------------ | ----------- |
| FPGA                                 | \$709.600   |
| Arduino Uno                          | \$40.000 |
| Protoboard                           | \$6.500 |
| Kit de sistema de refrigeración termoeléctrico Peltier | \$150.000  |
| Termocupla DS18B20                    | \$11.000    |
| Modulos Reles                        | \$21.000    |
| Resistencias y otros componentes electrónicos básicos       | \$15.000    |
| Final de Carrera   | \$3.500 |
| **Total**                            | **\$956.600** |

## Diagramas

- Diagrama de caja negra

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/4c403ed4-c8fd-4574-b67f-4602c1a3d1cb)

-Diagrama en Digital

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/86ba3672-d12e-4485-a135-ba19b1fb7eeb)


## Simulación 

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/1f2b8ee3-f52e-4e1a-aaa1-dd92f8abc356)
## Codigo en Verilog

```verilog
/*
 * Generated by Digital. Don't modify this file!
 * Any changes will be lost if this file is regenerated.
 */

module NEVERA (
  input A,
  input B,
  input C,
  input D,
  input E,
  input F,
  output G,
  output H,
  output I,
  output J,
  output K,
  output L,
  output M,
  output N,
  output O,
  output P,
  output Q,
  output R,
  output S,
  output T,
  output U,
  output V
);
  wire s0;
  wire s1;
  wire s2;
  wire V_temp;
  wire s3;
  wire s4;
  assign G = (A | (B & D) | (B & C));
  assign I = (A | B | (C & E) | (C & D));
  assign J = (A | (B & D) | (B & C));
  assign K = (A | (B & D) | (B & C));
  assign V_temp = ~ A;
  assign s0 = ~ B;
  assign s1 = ~ C;
  assign s2 = ~ D;
  assign s4 = ~ E;
  assign s3 = ~ F;
  assign L = (A | (s0 & C & E) | (s0 & C & D) | (B & s1 & s2));
  assign M = ((V_temp & B & D) | (V_temp & B & C));
  assign N = (A | (B & E & s3) | (s0 & s2 & s3) | (s0 & D & F) | (B & s2 & F) | (B & s1 & s3) | (C & s4 & F) | (C & D & s4) | (s1 & E));
  assign O = (A | (s0 & D & E & s3) | (s0 & s1 & D & s4) | (s0 & C & D & E) | (B & s1 & s2 & E) | (B & s4 & s3) | (B & C & s4) | (C & E & s3) | (C & s2 & s4));
  assign P = (A | (B & E & F) | (B & s1 & F) | (B & s1 & E) | (s0 & s2) | (s1 & E & F) | (C & s4 & s3) | (C & D & s3) | (C & D & s4) | (D & s4 & s3));
  assign Q = (A | (B & s2 & s3) | (s0 & D & s4) | (B & s1 & E) | (s0 & C & D) | (s1 & E & s3) | (s1 & s2 & E) | (C & s4));
  assign R = (A | (s0 & s1 & D) | (B & s4) | (B & s2) | (C & E) | (s2 & s4) | F);
  assign S = (A | (B & C & s2 & s4 & F) | (s0 & D & s4 & F) | (s0 & C & s4 & s3) | (s0 & C & D & F) | (s0 & s1 & s2 & E) | (B & s1 & D & E) | (B & D & s3) | (s1 & E & s3) | (s1 & s2 & s3) | (s2 & E & s3));
  assign T = (A | (B & C & s2 & s4 & F) | (s0 & C & s4 & s3) | (B & D & s3) | (s1 & E & s3) | (s1 & s2 & s3) | (s2 & E & s3));
  assign U = ((V_temp & C & E) | (V_temp & C & D) | (V_temp & B));
  assign H = A;
  assign V = V_temp;
endmodule
);


## Fotografías del Montaje

![Montaje](https://github.com/angelesmes/Lab.Digital1/assets/143465169/b3501350-f358-485e-8d37-e63e8e18e6c1)

## Vídeo de Funcionamiento

https://drive.google.com/file/d/1hZyHo432eGiXOAI4GWSE7KCx-eaXyO22/view?usp=sharing

https://drive.google.com/file/d/10YvCIvFgzs86eMYjiPFN9y1V4U9pTFvF/view?usp=sharing

## Bibliografía
1. "DANE - Encuesta nacional del uso del tiempo (ENUT)". DANE - Inicio. Accedido el 30 de noviembre de 2023. [En línea]. Disponible: https://www.dane.gov.co/index.php/estadisticas-por-tema/pobreza-y-condiciones-de-vida/encuesta-nacional-del-uso-del-tiempo-enut



