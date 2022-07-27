# numpy_cheat_sheet
### Creating an array
      >>> a = np.array([1,2,3])
      >>> b = np.array([(1.5,2,3), (4,5,6)], dtype = float)
      >>> c = np.array([[(1.5,2,3), (4,5,6)], [(3,2,1), (4,5,6)
          dtype = float)
    
### Inspecting array
     >>> a.shape           #Array dimensions
     >>> len(a)            #Length of array
     >>> b.ndim            # Number of array dimensions
     >>> e.size            #Number of array elements
     >>> b.dtype           #Data type of array elements
     >>> b.dtype.name      #Name of data type
     >>> b.astype(int)     #Convert an array to a different type
     
### Asking ffor help
     >>> np.info(np.ndarray.dtype)
     
### Initial Placeholder
     >>> np.zeros((3,4))                     #Create an array of zeros
     >>> np.ones((2,3,4),dtype=np.int16)     # Create an array of ones
     >>> d = np.arange(10,25,5)              #Create an array of evenly spaced values (step value)
     >>> np.linspace(0,2,9)                  #Create an array of evenly spaced values (number of samples)                                        
     >>> e = np.full((2,2),7)                #Create a constant array
     >>> f = np.eye(2)                       #Create a 2X2 identity matrix
     >>> np.random.random((2,2))             #Create an array with random value                                                                    
     >>> np.empty((3,2))                     #Create an empty array
### I/O
### Saving & Loading On Disk
     >>> np.save('my_array', a)
     >>> np.savez('array.npz', a, b)
     >>> np.load('my_array.npy')
     
