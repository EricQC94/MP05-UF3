# MP05-UF3
# UML

## Diagrama de Classes

Una classe és una representació d'un objecte (tangible o intangible) per a ser utilitzat en un programa.

Un diagrama de classes representa les classes que s'utilitzaran dins el sistema i les relacions existents entre elles.

Una classe consta de tres parts principals:
- Nom.
- Atributs.
- Funcions o mètodes.

Representació d'una classe en UML:

![image](https://user-images.githubusercontent.com/110727546/221841590-a3b79ca3-718b-4afa-a12a-d6a7122794f3.png)

**Exemple:** d'exemple farem servir la classe animal

### Nom

El nom de la classe ha de ser representatiu de què és en sí la classe.

![image](https://user-images.githubusercontent.com/110727546/221841686-73c5d8e8-8c25-4184-8695-37f65e3259fe.png)

### Atributs

Els atributs són valors importants de la classe (importants per al nostre programa), també se'ls coneix com propietats o camps.

A la nostra classe animal podem definir alguns atributs com:
- idAnimal (número sencer)
- nom (text)
- edat (número sencer)
- pes (número decimal)

La classe quedaria així:

![image](https://user-images.githubusercontent.com/110727546/221842112-1a15be2b-eee0-412b-ac31-9e2e2029f57b.png)

Però hem de definir també el tipus de dades de cada atribut així que ho especifiquem:

![image](https://user-images.githubusercontent.com/110727546/221849804-d2103b76-93e2-463b-9f73-d2d845271e1c.png)

### Visibilitat

Per últim hem de definir la visibilitat de cada atribut. 

La visibilitat indica qui té accés a l'atribut, hi ha tres valors de visibilitat:
- pública: Pot ser accedit des de qualsevol classe. Símbol (+).
- privada: Només poden ser accedits per la mateixa classe. Símbol (-).
- protegida: Només poden ser accedits per classes del mateix mòdul o subclasses. Símbol (#).
- package: Només pot ser accedit per classes del mateix paquet. Símbol (~).

Així els atributs de la classe, al ser privats quedaran:

![image](https://user-images.githubusercontent.com/110727546/221849729-a50c53b4-801a-4878-a354-9ec244fe07c6.png)

### Operacions

Les operacions o mètodes són funcionalitas de la classe, serveixen per modificar els atributs, realitzar càlculs o altres operacions...

Definirem uns mètodes públics per la nostra classe animal:
- possarNom(nom): Canvia el nom de l'animal pel que li passem.
- pesar(): Retorna el pes de l'animal.
- alimentar(): Donar menjar i aigua a l'animal.

La classe quedarà així:

![image](https://user-images.githubusercontent.com/110727546/221849946-c16e0ebb-2a58-4791-9c7c-c91a0a1d9524.png)

🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻

# Activitat

Utilitzarem [Lucid](https://lucid.app/) per crear els diagrames de classes següents:

1. persona.
2. llibre.
3. vehicle.
4. ordinador.

Penseu els seus atributs i operacions així com la visibilitat dels mateixos.


🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺

# Resposta de classe:

![image](https://user-images.githubusercontent.com/110727546/222085209-7007fd57-b632-40b2-8a98-6ff2682dc75a.png)

### Objectes

Els objectes són personalitzacions concretes d'una classe, instàncies, espais de memòria amb valors.

Si tenim la classe animal, aquesta defineix a tots els animals possibles, però quan pensem en un animal concret ja és un objecte de la classe animal.

Per exemple, si tenim un gos de 5 anys que es diu "Sultán" i pesa 41kg. Ja no parlem de classe, ara parlem d'un objecte d'una classe o d'una instància de la classe animal.

![image](https://user-images.githubusercontent.com/110727546/221941756-229fbcbe-43ca-49f0-ae5b-c09c7275f333.png)


![image](https://user-images.githubusercontent.com/110727546/221847922-d427d5e8-b422-4ed1-a88e-22a8beb63f15.png)
![image](https://user-images.githubusercontent.com/110727546/221850115-31cf0039-5c6b-4692-a8ea-d406f7884350.png)

## Herència

La classe animal és molt amplia, imagineu que el nostre programa servirà per gestionar diferents parts d'un zoo, hi ha animals que tenen comportaments que no tenen altres, per exemple ens fixem en la secció que cuida les tortugues i la que cuida les ovelles.

Les tortugues hivernen i les ovelles s'han d'esquilar, així que aprofitem que tenen coses comunes a la classe animal i heredem de la classe els seus atributs i mètodes i generem una classe "filla" amb els mètodes i atributs específics.

![image](https://user-images.githubusercontent.com/110727546/221852144-cdc717ea-8680-4cd0-b811-a473aa5c7df3.png)

A l'exemple animal és una **superclasse**, mentre que tortuga i ovella són **subclasses**, la superclasse és una generalització mentre que la subclasse és una especialització.

L'herència es representa amb una fletxa que surt de la subclasse i va a la superclasse.

🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻
# Activitat

Utilitzarem [Lucid](https://lucid.app/) per crear 5 generalitzacións de classes (subclasse i superclasse):

1. persona
2. ordinador
3. animal
4. telèfon
5. vehicle

https://lucid.app/lucidchart/b2c4cc06-1d6d-4edf-b732-482dd469376f/edit?page=0_0&invitationId=inv_aefa69ff-d1cd-4108-ae66-8fe1c03764da#

🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺

Exemple:

![image](https://user-images.githubusercontent.com/110727546/222091025-91c17b10-c1c9-4303-9194-50e89abd6c9a.png)

![image](https://user-images.githubusercontent.com/110727546/222092463-05000805-4bd0-4cb4-8fac-8451b3a13565.png)

## Relació

Hi ha vegades que dues classes estan relacionades sense ser parents, per exemple: una tortuga pot menjar-se un altre animal, com una medusa.

La relació rep un nom, en aquest cas "menja" i es representa per una línia sense fletxes.

![image](https://user-images.githubusercontent.com/110727546/221935154-2a8b5e23-63e6-4c1b-bb53-c4a7357f18ce.png)

Quan les relacions són entre diferents classes s'anomenen **associacions**.

Les relacions de vegades involucren més d'una instància de cada classe, en l'exemple següent tenim les classes persona i habitació:

![image](https://user-images.githubusercontent.com/110727546/221986963-8035bda1-bb08-4193-9d2e-a58c9feabc23.png)

On podem veure que **UN ÚNIC** objecte de la classe persona  pot fer una reserva d'**UNA O MÉS D'UNA** habitacions.

Per a representar la cardinalitat de les associacions fiquem dos números, un a cada costat de la mateixa. 

![image](https://user-images.githubusercontent.com/110727546/221987681-41e5a952-edcc-48ab-8d17-ed2f43fac446.png)

🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻

# Activitat

Escrivim quines associacions poden tenir les següents classes, nom d'associació i cardinalitat:

1. persona, DNI.
2. persona, comics.
3. persona, tren.
4. animal, persona.
5. persona, persona.
6. persona, cotxe.
7. persona, adreça.
8. taxi, client.

https://lucid.app/lucidchart/d1e526be-5f28-4720-b182-cd5594e4b1e7/edit?page=0_0&invitationId=inv_99ea34d9-3f68-460c-a2e7-21dd4bac244a#

🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺

### Resposta de classe:

![image](https://user-images.githubusercontent.com/110727546/225239025-46e1c84f-01e3-4615-846c-9a851fb8476b.png)


## Agregació

Es tracta d'un cas especial d'associació entre dos o més objectes.

Un objecte anomenat base que podrà incloure l'altre tipus d'objectes, com si fos un contingut.

L'objecte base necessita de l'objecte inclòs per existir, però l'objecte inclòs, si desapareix l'objecte base segueix existint.

Exemple: 

Objecte base fruiteria i objectes inclosos diferents tipus de fruita.

![image](https://user-images.githubusercontent.com/110727546/221990480-bbc41b4e-0480-4b82-b06c-ade03f6b4bf5.png)

Les agregacions es representen amb una línia contínua amb un romb buit a l'extrem de l'objecte base.

En aquest exemple si desapareix la fruiteria, les fruites seguiran existint.

🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻

# Activitat

Utilitzarem [Lucid](https://lucid.app/) per crear una agregació entre:

1. ovelles, corral.
2. animals, zoo.
3. curs, estudiants.
4. biblioteca, llibres.
5. atletes, equip.

https://lucid.app/lucidchart/708b9101-d3dc-40da-b474-81d1619b524b/edit?page=0_0&invitationId=inv_bdafc847-9447-4653-85c3-93674e83ddb9#

🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺

### Resposta de classe:

![image](https://user-images.githubusercontent.com/110727546/225244641-b530a6f5-9da4-4ea3-bf07-05b5c4fb1f77.png)


## Composició

És molt similar a la relació d'agregació, en aquest cas hi ha un objecte base que necessita dels objectes inclosos per a existir, però si desapareix l'objecte base també desapareixen els objectes inclosos.

Un objecte base "es composa" dels objectes inclosos.

La relació d’associació de composició es representa mitjançant una línia contínua finalitzada en un dels extrems per un rombe pintat, omplert. El rombe pintat s’ubicarà a la part de l’objecte base.

Exemple:

![image](https://user-images.githubusercontent.com/110727546/221994886-56d968aa-4b5b-4788-afeb-734d974831f9.png)

🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻

# Activitat

Utilitzarem [Lucid](https://lucid.app/) per crear 5 relacions de composició:

1. ordinador
2. pistola 
3. mar
4. cotxe
5. paella

https://lucid.app/lucidchart/b823b5c4-0bde-495e-87d3-a33509a635c2/edit?page=0_0&invitationId=inv_d3393fe5-86de-44b8-b351-e2fdb00ca2e4#

🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺

### Resposta de classe:

![image](https://user-images.githubusercontent.com/110727546/225249525-09f63feb-463e-4260-a124-df9d771497f0.png)


## Classe associativa

Hi ha vegades que una associació entre classes té propietats o mètodes propis, llavors aquesta es representa amb una línia discontinua unida a la línia d'associació.

La línia i la classe nova representen el mateix element conceptual de l'associació.

A l'exemple següent tenim una associació entre la classe **estudiant** i la classe **assignatura**, l'associació es diu **està cursant** i té la propietat pròpia **nota**.

![image](https://user-images.githubusercontent.com/110727546/224995926-e23c4041-ddb0-41b3-a489-3e5da197df73.png)

🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻

# Activitat

Utilitzarem [Lucid](https://lucid.app/) crea 2 relacions d'associació amb operacions o atributs propis:

1. restaurant, cambrer - estaTreballant
2. local, visitant - partit

https://lucid.app/lucidchart/a13fc867-5bc2-42f1-ade9-c67d4d676c8c/edit?page=0_0&invitationId=inv_8523bfba-df84-4d52-9059-418a31af9acf#

🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺

### Resultat classe:

![image](https://user-images.githubusercontent.com/110727546/225254264-1959e788-79e4-4492-a92f-4f88a1d38fe0.png)

## Interfície (interface)

La interfície és una classe abstracta que conté la declaració (i només la declaració) de les propietats i operacions que s'hauran d'implementar per una classe.

Per exemple aquí tenim la interfície ICalculadora:

![image](https://user-images.githubusercontent.com/110727546/224996694-1cd775e9-c6d8-4ef1-b757-b092775155b7.png)

Com veiem té la declaració dels mètodes, aquesta interfície es podria codificar així:

```
interface ICalculadora {
    public abstract int suma (int x, int y);
    public abstract int resta (int x, int y);
    public abstract int multiplicacio (int x, int y);
    public abstract int divisio (int x, int y);
}
```

Si volem utilitzar ICalculadora haurem de crear una classe que la implementi, per exemple la classe laMevaCalculadora:

```
public class laMevaCalculadora implements ICalculadora {
        public int suma (int x, int y){
            return x + y;
        }
        public int resta (int x, int y){
            return x - y;
        }
        public int multiplicacio (int x, int y){
            return x * y;
        }
        public int divisio (int x, int y){
            return x / y;
        }
}
```

🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻

# Activitat

Utilitzarem [Lucid](https://lucid.app/) i IntelliJ crea 2 interfícies, la seva codificació a Java i una classe que la implementi.

1. ![Selecció_213](https://user-images.githubusercontent.com/113598440/229057159-9720edcb-404a-483f-91e5-bb026ef6b70d.png)

```
package MP05;

import javax.print.DocFlavor;

interface butlleti2 {
    public abstract int nota (int nota);
    public abstract String Suspes (String Suspes);
    public abstract String Aprovat (String Aprovat);
    public abstract String Notable (String Notable);
    public abstract String Excelent (String Excelent);
}
```

```
package MP05;
public abstract class butlleti implements butlleti2 {
    public static void main(String[] args) {
        int nota = 5;
        String Suspes = "Suspes";
        String Aprovat = "Aprovat";
        String Notable = "Notable";
        String Excelent = "Excelent";

        if (nota <= 4){
            System.out.println(Suspes);
        } else if (nota <= 6) {
            System.out.println(Aprovat);
        } else if (nota <= 8) {
            System.out.println(Notable);
        } else if (nota <= 10) {
            System.out.println(Excelent);
        }

    }

    @Override
    public int nota(int nota) {
        return 0;
    }

    @Override
    public String Suspes(String Suspes) {
        return Suspes;
    }
    @Override
    public String Aprovat(String Aprovat) {
        return Aprovat;
    }
    @Override
    public String Notable(String Notable) {
        return Notable;
    }
    @Override
    public String Excelent(String Excelent) {
        return Excelent;
    }

}
```


2.

🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺
# Utilitzar diagrames de classe per generar codi.

## Formes:

Tenim aquest diagrama de classes:

![image](https://user-images.githubusercontent.com/110727546/226755761-8b6c8dab-6f08-4b03-801e-c062957e8cc3.png)

🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻

1. Com serà el codi en Java que implementi aquest diagrama?

```
public class forma {
    public int posicioY;
    public int posicioX;

    public void dibuixar(){

    }
}
class quadrat extends forma{
    public int costat;
}

class rectangle extends forma{
    public int ample;
    public int alt;
}

class cercle extends forma{
    public int radi;
}
```


🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺

## Estudiant:

![image](https://user-images.githubusercontent.com/110727546/226758128-fe3f1e77-8c76-434a-bf1b-2e923d7251bc.png)

🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻

2. Com serà el codi en Java que implementi aquest diagrama?

```
public class Persona {
    public String ciutat;
    public String cognoms;
    public int telefon;
    public int CP;
    public String DNI;
    public String adreça;
    public String nom;

}

class Institut{
    public int telefon;
    public int CP;
    public String ciutat;
    public String nom;
    public String adreça;
}
class Estudiant extends Persona{
    private Institut estudia= new Institut();

    public void matricula (Institut matriculat){
        System.out.println("S'ha matriculat a" + matriculat);
        this.estudia=matriculat;
    }
    
class Estudiant extends Persona{
    private Institut estudia= new Institut();

    public void matricula (Institut matriculat){
        System.out.println("S'ha matriculat a" + matriculat);
        this.estudia=matriculat;
    }
```

🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺

## Llista de contactes:

Un diagrama de classe es genera per les especificacions del nostre projecte, quant més precisses més fiable serà el diagrama generat.

Anem a ficar un exemple d'una llista de contactes.

Volem tenir un programa que guardarà una llista de contactes, cada contacte tindrà la següent informació: 

- nom.
- cognoms.
- número de telèfon.
- adreça.
- codi postal.
- ciutat

La llista de contactes ens permetrà mantenir un número de contactes indefinits i tindrà les opcions de afegir contactes i mostrar contactes.

🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻

3. Com serà el diagrama de classes d'aquest programa?

4. Com serà el codi en Java que l'implementi?



🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺


### Diagrama de  classes:

![image](https://user-images.githubusercontent.com/110727546/226751462-2eae4ad4-560d-442d-adee-f6167c7347e8.png)




### Codi:

- Classe contacte:

```
class contacte {
    public String nom;
    public String cognoms;
    public int telefon;
    public String adreca;
    public int CP;
    public String ciutat;

    public contacte(String nom, String cognom, int telefon, String adreca, int CP, String ciutat) {
        this.nom = nom;
        this.cognoms = cognom;
        this.telefon = telefon;
        this.adreca = adreca;
        this.CP = CP;
        this.ciutat = ciutat;
    }
}
```

- Classe llistaContactes:

```
import java.util.ArrayList;
import java.util.ListIterator;

class llistaContactes {
    private ArrayList<contacte> contactes = new ArrayList<>();
    public void afegirContacte(contacte c){
        contactes.add(c);
    }
    public void imprimirContacte(String nom){
        ListIterator<contacte> it = contactes.listIterator();
        contacte c;
        while(it.hasNext()){
            c = it.next();
            if (c.nom.equals(nom)){
                System.out.println("Dades de contacte");
                System.out.println("Nom: "+c.nom);
                System.out.println("Cognoms: "+c.cognoms);
                System.out.println("Telèfon: "+c.telefon);
                System.out.println("Adreça: "+c.adreca);
                System.out.println("Codi Postal: "+c.CP);
                System.out.println("Ciutat: "+c.ciutat);
            }
        }
    }
}
```

- Programa main per provar el codi:

```
public class Main {
    public static void main(String[] args) {

        llistaContactes l = new llistaContactes();
        contacte c = new contacte("Xavi","Sancho",555443322,"Carrer de París, 4-1",08028,"Barcelona");
        l.afegirContacte(c);
        l.imprimirContacte("Xavi");
    }
}
```

🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻

Ara modifiquem el programa per a que es pugui afegir un contacte preguntant a usuari les dades directament, també es pugui eliminar un contacte o modificar les seves dades, per a fer-ho afegirem els mètodes i atributs necessaris a les classes implicades.

5. Com serà el diagrama de classes del programa ara?
6. Com serà el codi en Java que l'implementi?

🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺

# Kahoot:

🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻

7. Feu un Kahoot per parelles de 15 preguntes sobre la teoria vista fins ara per a practicar per a l'examen de teoria del proper dia.

🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺

## Biblioteca:

Tenim el següent diagrama de classes que representa el sistema de prèstec d'una biblioteca:

![image](https://user-images.githubusercontent.com/110727546/226762784-602b8ca7-bc2c-4baa-8ecb-44f641e4e13b.png)

🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻🔻

8. Com serà el codi en Java que l'implementi?

🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺🔺


