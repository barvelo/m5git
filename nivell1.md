# Java (llenguatge de programació)

El **Java** és un llenguatge de programació dissenyat el 1990 per _James Gosling_ amb altres companys de **Sun Microsystems a partir del llenguatge C.** Des del seu naixement fou pensat com un llenguatge orientat a objectes. Entre el 13 de novembre de 2006 i el maig del 2007 Sun va alliberar parts de Java com a **_programari lliure de codi obert amb llicència GPL_**. És un dels llenguatges de programació més utilitzats, i s'utilitza tant per aplicacions web com per aplicacions d'escriptori.[1][2]

El Java és un llenguatge compilat amb una màquina virtual d'intermediari i, per tant, pot semblar lent en comparació amb altres llenguatges, però ofereix un índex de re-utilització de codi molt elevat, sent possible trobar moltes llibreries lliures de Java. És un llenguatge flexible i potent tot i la facilitat amb la qual es programa i dels resultats que ofereix. Un dels trets que el caracteritza i que el fa una eina molt valorada a l'hora de desenvolupar aplicacions distribuïdes, és el fet que és un llenguatge multi-plataforma.

### Característiques de Java

- **Senzill**: Java s'ha creat perquè sigui un llenguatge senzill amb una sintaxi elegant. Únicament consta de tres tipus de dades primàries, eliminant els punters i l'herència múltiple

  - **Orientat a objectes**: Java segueix els paradigmes de la programació orientada a objectes, ja que la programació amb Java se centralitza en la manipulació, creació i construcció d'objectes.

    - **Distribuït:** Java permet la construcció d'aplicacions distribuïdes per mitjà d'una col·lecció específica de classes.

- **Interpretat:** Es necessita un intèrpret per executar els programes de Java, això alenteix als programes però els hi dona flexibilitat.

  - **Robust:** Java és un llenguatge robust i fiable, s'ha escrit pensant a poder verificar errors i està molt tipificat.

  - **Segur:** Java té pocs problemes de seguretat, característica molt important en les aplicacions distribuïdes d'Internet.

- **Arquitectura neutral:** Java és independent de la plataforma final on s'executarà el programa.

- **Portable:** Java és un llenguatge d'alt nivell i de plataforma independent, això li dona portabilitat.

- **Alt rendiment:** Els compiladors Java han anat millorant les seves prestacions. Els nous compiladors

### Tipus de Dades

####  Tipus de dada primitius o variables primitives

> Article principal: [Tipus de dada primitius](https://ca.wikipedia.org/w/index.php?title=Tipus_de_dada_primitius&action=edit&redlink=1)

```java
int n1 = 12 ; 
short n2 = 0 ;
char n3 = o ;
byte n3 = 0 ;
short n3 = 0 ;
long n3 = 0L ;
float n3 = 0.0f ;
double n3 = 0.0 ;
boolean n3 = false ;
```  
 
##### BOOLEÀ (boolean)
Només pot tenir el valor true o false.

##### CARÀCTER (char) 

Utilitzen 16 bits i codifiquen caràcters segons el format UNICODE (no com ASCII que fa servir 8 bits). El Tipus de dada char és un dígit individual, sense signe el qual es pot representar com numèrics.

##### NUMÈRICS ENTERS (byte, short, int, long) i NUMERICS REALS (fload, double)

Els valor literals dels dígits poden ser escrits en base 10, hexadecimal i octal. Els valors numèrics decimals, la coma ha de ser un punt.

### Sintaxi

> La sintaxi del Java deriva en gran part del C. Però a diferència d'aquest, que combina la sintaxi per a programació genèrica, estructurada i orientada a objectes, el Java va ser dissenyat gairebé exclusivament com a llenguatge orientat a objectes Tot el codi es troba dins d'una classe, i tot és un objecte (excepte nombres ordinals i reals, booleans i caràcters per motius de rendiment)

``` java

// Hola.java
import java.io.IOException;
public class Hola {
    public static void main(String[] args)throws IOException {
        System.out.println("Hola, món!"); 
    }
}

```

# Enlaces externos

[Java a Sun Microsystems](https://www.oracle.com/java/technologies/)

[Sun - Especificació del llenguatge Java](https://docs.oracle.com/javase/specs/)

[API de la biblioteca JavaSE](https://docs.oracle.com/javase/6/docs/api/)

[Sun - Noves característiques de Java 5 (angl)](https://docs.oracle.com/javase/6/docs/api/)
