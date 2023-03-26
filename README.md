# MP05-UF3
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

