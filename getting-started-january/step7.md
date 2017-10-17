Datasets also provide a straightforward way to create an array initialized with random numbers.

To create a dataset with random data we first need to import the random class.

`import org.eclipse.january.dataset.Random`{{execute}}

Then, use the code below to create a random dataset.

`Dataset another =  Random.rand(3, 5)`{{execute}}

`System.out.println(another.toString(true))`{{execute}}
