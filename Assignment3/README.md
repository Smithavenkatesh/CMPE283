Add counters into the KVM that track the following information:

  • Total number of exits (for each type of exit KVM enables)
  
  • Max/Min/Average number of CPU cycles for each exit type
  
  • Total amount of cycles spent processing all exits
  
An ideal place to implement this functionality is inside the top-level exit handler function in KVM. 


