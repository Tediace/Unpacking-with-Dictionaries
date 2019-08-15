# Unpacking-with-Dictionaries 
Unpacking dictionaries is the opposite of packing them. It can be used if you have an existing dictionary that you would like to send to a function.

<br>Consider this code:</br>
```python
teacher = {
  'name':'Ashley',
  'job':'Instructor',
  'topic':'Python'
}

def print_teacher(name, job, topic):
    print(name)
    print(job)
    print(topic)
```    
First, we have a dictionary called `teacher` that holds three key:value pairs: name, job, and topic, each with 
<br>corresponding values.</br>

<br>Then, we have a function called print_teacher that receives three arguments, name, job, and topic.
To pass the data from the teacher dictionary to this function, we can use unpacking to easily and quickly 
extrapolate the data into a format the function will accept.</br>

<br>To do that, we use a function call where the passed argument is `**teacher`. print_teacher(**teacher)
This `**` unpacks all the key:value pairs in the `teacher` dictionary into three keyword arguments, which 
are then accepted by the function into the three corresponding parameters.</br>
