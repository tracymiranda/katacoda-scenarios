Datasets also provide a straightforward way to create an array initialized with a range of numbers.
To create a dataset with a range use the code below.

`Dataset dataset = DatasetFactory.createRange(15, Dataset.INT32).reshape(3, 5)`{{execute}}

`System.out.println(dataset.toString(true))`{{execute}}


