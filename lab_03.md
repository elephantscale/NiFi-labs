# Lab 03
## Data Generator

* Create a processor that generates data

![](images/01.png)

* Create a processor that reads data
* Look for GenerateFlowFile

![](images/02.png)


* Add the GenerateFlowFile processor to the flow
* It will have a warning - that's OK, it is not configured yet

![](images/03.png)

* Let's configure the processor

![](images/04.png)

* Let's go to the properties tab


![](images/05.png)

* Analyze and explain each of the properties

* Let's set the properties
* File size - 1B
* Batch size - 5
* We don't want unique FlowFiles

![](images/06.png)


* Now let's go to Schedule tab

![](images/07.png)

* Pay attention to the run schedule
* This is how often the processor will run

![](images/08.png)

* This means that the processor will run every 10 seconds and create 5 FlorFiles

* Now, add another Processor and configure it as ReplaceText

![](images/09.png)

* Connect the two processors

![](images/10.png)

* For relationship success

![](images/11.png)

* And now, start the first processor, the GenerateFlowFile processor

![](images/12.png)

* Watch how more and more bytes are queued up

![](images/13.png)

* Stop the first processor and let us configure the second processor


![](images/14.png)

* Configure the ReplaceText processor to replace the text with "Hello world"


![](images/15.png)

* That's it! You get as much test data as you want!!

![](images/16.png)

### Congratulations!

