# Programming styles



Programming language has two main roles:

- Communicate human to computer
- Communicate humans to humans

Programmers main goal is build good programs, but, what does a good program mean?



**Style programming qualities**

- Extensibility (Extensibilidad)

  Ease with software can adapt to the future changes.

- Verifiability (Verificabilidad)

  Ease with that can we check system properties .

- Reparability (Reparabilidad)

  Fix errors possibility without struggling.

- Evolution capacity (Capacidad de evolucion)

  Adapt to new requirements.

- Understandability (Comprensibilidad)

  Ease with programmers learning.

**Additional considerations **

- Style code is not the final result, it is to do in the progress of the project.
- Usually is most difficult fix a code after finish it than  write it good from the beginning.
- All the projects have the same code style.
- Indentation has to show the code structure without read the code.



## Indentation

It is used to read the code easily.



**Indentation styles**

- K&R

  ```php
function xd() {
  	if(true) {
  		echo" xd";
  	}
  	else {
  		echo "Imposible";
  	}
  }
  ```
  
- Allman

  ```php
  function xd() 
  {
  	if(true) 
  	{
  		echo" xd";
  	}
  	else 
  	{
  		echo "Imposible";
  	}
  }
  ```

- BSD KNF

  Also termed Kernel Normal Form,  it is a variant of K&R style, but the difference consists in the number of tabs that it use.

  ```php
  function xd() {
  		//Aqui existe una linea
  		if(true) {
  				echo" xd";
  		}
  		else {
  				echo "Imposible";
  		}
  }
  ```

- Whitesmiths 

  The code and the brackets are in the same indentation level.

  ```php
  function xd() 
  	{
  	if(true) 
  		{
  		echo" xd";
  		}
  	else 
  		{
  		echo "Imposible";
  		}
  	}
  ```

- GNU

  It use 2 empty spaces when we open a new bracket and another 2 additional empty spaces for the content.
  
  ```php
  function xd() 
    {
      if(true)
        {
  	    echo" xd";
  	  }
      else 
  	  {
  	    echo "Imposible";
        }
  	}
  ```



 