Datasets also provide a straightforward way to create an array initialized with a range of numbers.
To create a dataset with a range use the code below.

`Dataset dataset = DatasetFactory.createRange(IntegerDataset.class, 15).reshape(3, 5)`{{execute}}

`System.out.println(dataset.toString(true))`{{execute}}


